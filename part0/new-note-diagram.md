```mermaid
    sequenceDiagram
        participant browser
        participant server
        
        browser->>server: POST 
        activate server
        server-->>browser: 302
        deactivate server
        
        browser->>server: GET HTML
        activate server
        server-->>browser: HTML Document
        deactivate server
        
        browser->>server: GET CSS
        activate server
        server-->>browser: CSS Document
        deactivate server
        
        browser->>server: GET JS
        activate server
        server-->>browser: JS Document
        deactivate server
        
```