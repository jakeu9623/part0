```mermaid
sequence diagram
  participant server
  participant browser
  participant event handler

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
  server->>browser: HTML document
  server->>browser: css file
  server->>browser: JavaScript file
  server->>browser: JSON file
  deactivate server
```





