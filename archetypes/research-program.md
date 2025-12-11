---
title: "{{ replace .Name "-" " " | title }}"
summary: ""
description: "Research program description for {{ replace .Name "-" " " }}."
date: {{ .Date }}
draft: true
type: "research-program"

schema:
  type: "ProgramDescription"
  version: "0.1"
---
