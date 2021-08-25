---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "images/portfolio/HAA10_{{ replace .Name "-" "" }}1.jpg"
categories: [HAA10]
draft: false
student_info:
- name: "{{ replace .Name "-" " " }}"
  icon: "fas fa-user"
  content: "--facebook--"
- name: "Công việc"
  icon: "fas fa-palette"
  content: "2D Artist"
# - name: "Link"
#   icon: "fas fa-link"
#   content: "https://artstation.com/{{ .Name }}"
---


##### • Bài tập thực hiện trong quá trình học:

![{{ .Name }}-assignment](/images/portfolio/HAA10_{{ replace .Name "-" "" }}2.jpg)



<!-- ##### • Nhận xét sau khoá học: -->
