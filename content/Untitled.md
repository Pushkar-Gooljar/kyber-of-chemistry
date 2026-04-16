/public/sy_maps contain json files that contain data about revision notes i made for 9701, 9702, and 9618 syllabuses for a level.

the notes are in html format available at fullmarxhtml.netlify.app/syllabuscode/topic/subtopic/concept.html

and in pdf format available at fullmarxpdf.netlify.app/syllabuscode/topic/subtopic/concept.pdf.

create a react app with typescript and scss to allow people to view these notes.
include a sidebar with accordion to view available notes.
for each note, have a download note button to download the pdf version
notes should be accessible at base_url/syllabuscode/topic/subtopic/concept 
ensure mobile responsiveness
add a theme context to take system theme as default but allow user to change and save in localstorage
to change the theme of the notes, you need to change the data-bs-theme attribute in teh <html> of the notes to light or dark
add a nice home page

app name is FullMarx