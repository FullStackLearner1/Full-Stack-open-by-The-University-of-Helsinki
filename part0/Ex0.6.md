```mermaid 

sequenceDiagram
participant browser
participant server

browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
activate server
Note left of server: 201 created
Note left of server: Adds the data to do list and sends the new note to the server
deactivate server