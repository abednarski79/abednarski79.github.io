# abednarski79.github.io / projects.appbucket.eu

The source code of my page containing list of my projects.

## How to add new project to the index page (quick and dirty):
- open https://github.com/abednarski79/abednarski79.github.io/edit/master/index.md
and add new entry in format:
```
- [newProjectName - One sentece description](https://github.com/codeforireland/new-project-name)
```
- commit changes wait few minutes and go to http://abednarski79.github.io to see result

## How to add new project to the index page (the right way):
- install jakyll for windows with rouge support: http://jekyll-windows.juthilo.com/ and http://jekyllrb.com/docs/windows/
- checkout the project and got to the folder using system terminal
- run command:

> jekyll serve

- open in text editor *index.md* page and add new entry in format:
```
- [newProjectName - One sentece description](https://github.com/codeforireland/new-project-name)
```
from that point on every change in the source of the project will cause re-generation of the page
- follow the steps in *How to add new post* and create new post presenting short descriptin of the new application
- open browser at: http://127.0.0.1:4000/ and check if your changes were correct
- when your are happy with result commit changes to github and go to http://abednarski79.github.io

## How to add new page:
- got to project folder
- create new file with extension *.md* for example *contact.md*
- at the beginning of the file enter:
```
---
layout: page
title: Projects
---
```
the rest of the content of the file must be in *GitHub Flavored Markdown*
- save the file and refresh the browser at: http://127.0.0.1:4000/
- when your are happy with result commit changes to github and go to http://abednarski79.github.io

## How to add new post:
- follow the instruction on: http://jekyllrb.com/docs/posts/
