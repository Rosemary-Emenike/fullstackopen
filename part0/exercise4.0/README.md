browser —> server: POST https://studies.cs.helsinki.fi/exampleapp/new_note + form data
server —» browser: HTTP status code

browser —> server: GET https://studies.cs.helsinki.fi/exampleapp/notes
server —» browser: HTML document

browser —> server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
server —» browser: The CSS file

browser —> server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
server —» browser: The Javascript file

browser —> server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
server —»browser: [ ..., { content: "New note", date: "2023-11-26" } ]
