---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "images/portfolio/{{ replace .Name "-" "" }}.jpg"
categories: ["HAA"]
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


### • Bài tập thực hiện trong quá trình học:

![{{ .Name }}](/images/portfolio/{{ replace .Name "-" "" }}.jpg)



### • Nhận xét sau khoá học:
