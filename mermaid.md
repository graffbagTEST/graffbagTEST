```mermaid
flowchart TD
  Build -->|Dependency available | Use
  Build -->|Dependency not available and env variable not set| Install
  Build -->|Dependency not available and env variable set| Fail
```
