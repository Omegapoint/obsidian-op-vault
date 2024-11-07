---
template_version: 1.1.1
created_date: <% tp.date.now("YYYY-MM-DD") %>
week_card: 
tags:
---
[[<% tp.date.now("YYYY-vww", `P-7D`, tp.file.title, "YYYY-vww") %>|← förra veckan]] ✪ [[<% tp.date.weekday("YYYY-MM", 0, tp.file.title, "YYYY-vww") %> | ↑ <% tp.date.weekday("MMMM", 0, tp.file.title, "YYYY-vww") %> ]]  ✪ [[<% tp.date.now("YYYY-vww", `P7D`, tp.file.title, "YYYY-vww") %>|nästa vecka→ ]]  
# Weekly note  <% tp.date.now("[(]vW[)], YYYY", 0, tp.file.title, "YYYY-[v]WW") %> 

- [[<% tp.date.now("YYYY-MM-DD", `0`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `0`, tp.file.title, "YYYY-vw") %>]] 
- [[<% tp.date.now("YYYY-MM-DD", `P1D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P1D`, tp.file.title, "YYYY-vw") %>]] 
- [[<% tp.date.now("YYYY-MM-DD", `P2D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P2D`, tp.file.title, "YYYY-vw") %>]] 
- [[<% tp.date.now("YYYY-MM-DD", `P3D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P3D`, tp.file.title, "YYYY-vw") %>]] 
- [[<% tp.date.now("YYYY-MM-DD", `P4D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P4D`, tp.file.title, "YYYY-vw") %>]] 
- ( [[<% tp.date.now("YYYY-MM-DD", `P5D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P5D`, tp.file.title, "YYYY-vw") %>]] | [[<% tp.date.now("YYYY-MM-DD", `P6D`, tp.file.title, "YYYY-vw") %>|<% tp.date.now("dd D/M", `P6D`, tp.file.title, "YYYY-vw") %>]] ) 


