---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: Becky Moody
date: {{ .Date }}

draft: true
output:
  html_document:
    keep_md: yes
always_allow_html: true

tags: []
image: index_files/
---