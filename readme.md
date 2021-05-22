```mermaid
sequenceDiagram
	Group->>Posts: Connect
	activate Group
	activate Posts
	Posts-->>Group: Options
	deactivate Group
	deactivate Posts
```
