# README

Welcome to the backend of our [website](http://digital-genius.github.io).

It is using a Jekyll Static Site Generator meaning that the content is all in the root directory and when the `jekyll build` command is run from the CLI it is collected into the pages and converted from Markdown or whatever format it is stored in into HTML which is stored in the `_Site` directory.

When a browser requests the site it is the HTML from this directory that is sent not any of the actual content and nothing is compiled on the fly as with PHP.

Because of this Static Site Generators are mutch quicker than other CMS (Content Management System) solutions.