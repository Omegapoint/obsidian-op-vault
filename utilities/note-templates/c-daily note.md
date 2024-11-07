---
template_version: 1.2.0
created_date: <% tp.date.now("YYYY-MM-DD",0, tp.file.title, "YYYY-MM-DD") %>
tags:
 - daily
related:

tracked:

---
# <% tp.date.now("LL, dddd [v]w ",0, tp.file.title, "YYYY-MM-DD") %>

## Todo today

```tasks
(due on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>) OR ( (has start date) AND (starts on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>) )

hide due date
```

## Day Log



## Sparks 



## General tasks

```tasks
not done
starts before tomorrow
NOT (due on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>)
```
