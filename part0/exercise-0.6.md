```mermaid

sequenceDiagram
participant browser
participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Note right of browser: The browser the new note as JSON data
    activate server
    server-->>browser: Server responds with 201 Created
    deactivate server
```
