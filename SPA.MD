```mermaid
sequenceDiagram
  participant browser
  participant server

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
  activate server
  server->>browser: HTML document
  server->>browser: css file
  server->>browser: JavaScript file
  server->>browser: JSON file
  deactivate server
```





