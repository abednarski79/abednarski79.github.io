# abednarski79.github.io

The source code of my page containing list of my projects.

## How to add new project to the index page (quick and dirty):
- open https://github.com/abednarski79/abednarski79.github.io/edit/master/index.md
and add new entry in format:
```
- [newProjectName - One sentece description](https://github.com/codeforireland/new-project-name)
```
- commit changes

## How to add new project to the index page (the right way):
- open in text editor *index.md* page and add new entry in format:
```
- [newProjectName - One sentece description](https://github.com/codeforireland/new-project-name)
```
- when your are happy with result commit changes to github and go to http://abednarski79.github.io

## How to build the page:
- install jakyll for windows with rouge support: http://jekyll-windows.juthilo.com/ and http://jekyllrb.com/docs/windows/
- checkout the project and got to the folder using system terminal
- run command:

> jekyll serve

from that point on every change in the source of the project will cause re-generation of the page
- open browser at: http://127.0.0.1:4000/



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
