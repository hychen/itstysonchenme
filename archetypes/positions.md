---
title: "{{ replace .Name "-" " " | title }}"
summary: ""
description: "Position statement on {{ replace .Name "-" " " }}."
date: {{ .Date }}
draft: true
type: "position"
weight: 1

schema:
  type: "PositionPaper"
  version: "0.1"

claims: []
assumptions: []
citations: []
---
