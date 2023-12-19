```mermaid
%% Example of sequence diagram
  sequenceDiagram
    Browser->>Server: Get https://studies.cs.helsinki.fi/exampleapp/notes
    alt 200 OK
    Server->>Browser: HTML document
    else 200 OK
    
    end
```