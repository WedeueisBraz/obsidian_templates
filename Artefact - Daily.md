---
tags:
  - Artefact/daily
date: ""
subject:
project:
client:
---

related: [[]]

-------------------------------------------------------------------------------
## TODO




-------------------------------------------------------------------------------
## DUE Today

```dataviewjs
dv.taskList(dv.pages().file.tasks
	.where(t => !t.completed)
	.where(t => t.text.includes("{{date:YYYY-MM-DD}}")))
```

-------------------------------------------------------------------------------
