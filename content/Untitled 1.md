I have these two json files

{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "title": "Classification Data",
  "type": "object",
  "description": "A dictionary mapping topic names to lists of question Group IDs.",
  "additionalProperties": {
    "type": "array",
    "items": {
      "type": "string",
      "pattern": "^GRP_\\d{4}$"
    }
  }
}

{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "title": "Question Data",
  "type": "object",
  "properties": {
    "threshold_used": { "type": "number" },
    "total_questions_analyzed": { "type": "integer" },
    "total_unique_concepts": { "type": "integer" },
    "question_groups": {
      "type": "array",
      "items": {
        "type": "object",
        "properties": {
          "group_id": { "type": "string" },
          "cluster_size": { "type": "integer" },
          "canonical_text": { "type": "string" },
          "appearances": {
            "type": "array",
            "items": {
              "type": "object",
              "properties": {
                "paper_id": { "type": "string" },
                "q_num": { "type": "string" },
                "exact_text": { "type": "string" }
              },
              "required": ["paper_id", "q_num", "exact_text"]
            }
          }
        },
        "required": ["group_id", "cluster_size", "canonical_text", "appearances"]
      }
    }
  },
  "required": [
    "threshold_used", 
    "total_questions_analyzed", 
    "total_unique_concepts", 
    "question_groups"
  ]
}

use them to create a python program that generate random mcq questions for 9702 a level physics. give the code


the following list contains the range of how many questions there should be per topic, max of 40 questions in total.
BOUNDS = {  
    "1 Physical quantities and units": (3, 5),  
    "2 Kinematics": (2, 4),  
    "3 Dynamics": (3, 5),  
    "4 Forces, density and pressure": (3, 5),  
    "5 Work, energy and power": (3, 5),  
    "6 Deformation of solids": (2, 3),  
    "7 Waves": (3, 5),  
    "8 Superposition": (2, 4),  
    "9 Electricity": (4, 6),  
    "10 D.C. circuits": (3, 5),  
    "11 Particle physics": (2, 4)  
}
lets say you need 3 questions for topic X
choose 3 random groups for topix X
go to that group in the data json,
choose the question from the lastest paper