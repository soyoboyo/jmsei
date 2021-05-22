```mermaid
sequenceDiagram
        User->>Group: Find a group you are not following
        activate User
        activate Group
        Group-->>User: Group
        User->>Group: Follow group
        Group->>Group: New Post
        deactivate Group
        deactivate User
```
