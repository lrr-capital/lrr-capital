# lrr-capital.github.io

Currently there are 3 precreated pages, use them as a model. Just make new Markdown (.md) or HTML (.html) files and link to them to create new pages. A Markdown file is simpler to use, but is less flexible, while an html file is slightly more difficult to use, but you have more control.

## Project Layout

### index.html

Home page

### about.md

About page

### research.md

Research page

### files/

Folder with static files such as pdfs or word docs. Add additional files to this folder to use  them. They can be linked to in markdown with `[Link text](/assets/[pdf-name].pdf)` or `<a href="/assets/[pdf-name].pdf">`

### images/

Folder with static images. To add image assets, add them to the `images` folder and link to them with `<img src="img-url">` tags or markdown `![Alt text](image url)` images.

### \_sass/

Styling assets

### \_layout

Page templates

### css/

Internal styling assets, only use them to set global variabes and import styles from the css folder

## Running this locally

Github automatically builds this into a website, but if you want to build it yourself follow this guide: https://jekyllrb.com/docs/. The website will be deployed to localhost:4000.
