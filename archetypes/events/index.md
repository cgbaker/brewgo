---
title: "{{ replace .Name "-" " " | title }}"
params:
  date: "{{ .Date.Format "2006-01-02" }}"
  location: ""
  event_url: ""
  charity: ""
  charity_url: ""
  image: ""
  beers: []
  recap: false
---

*Event description here.*
