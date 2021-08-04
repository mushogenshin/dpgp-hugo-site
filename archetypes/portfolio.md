---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "images/portfolio/{{ replace .Name "-" "" }}.jpg"
categories: []
draft: false
student_info:
- name: "{{ replace .Name "-" " " }}"
  icon: "fas fa-user"
  content: "https://facebook.com/{{ .Name }}"
- name: "Công việc"
  icon: "fas fa-palette"
  content: "2D Artist"
- name: "Link"
  icon: "fas fa-link"
  content: "https://artstation.com/{{ .Name }}"
---