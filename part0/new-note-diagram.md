```mermaid
    sequenceDiagram
        participant browser
        participant server
        
        browser->>server: POST 
        activate server
        server-->>browser: 302
        deactivate server
```