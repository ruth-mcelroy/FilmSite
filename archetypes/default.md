---
title: "{{ replace .Name "-" " " | title }}"
date: "{{ .Date }}"
image: "{{ .Name }}.jpg"
categories: ["Ricoh 500g",
"Flexaret VI", 
"Olympus OM1", 
"Olympus 35rc", 
"Agfa Billy Clack",
"Panasonic GF7"]

---
[One line Location/Theme description]
<!--more--> 
  {{% foldergallery src = "{{ .Name }}" %}}

