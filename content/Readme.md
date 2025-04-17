# Welcome to Polycentric

### A role-playing game of agreements

## How to Contribute

The knowledge commons is built on simple [markdown](https://www.markdownguide.org/cheat-sheet/) files and served as a website through [Quartz](https://quartz.jzhao.xyz/).

## Get Started

1. Download [Obsidian](https://obsidian.md/download)

   Obsidian provides a nice UI for authoring Markdown content.

2. Clone and setup the repo https://github.com/oovg/polycentric

````
``` git clone https://github.com/oovg/polycentric
``` cd quartz
``` yarn
``` yarn quartz build --serve
````

3. Open the /content folder as a vault in Obsidian
   Create and Edit content with files and folders within Obsidian
4. Request access to push your updates back to [Github](https://github.com/oovg/polycentric).
5. Create a pull request from `your-branch-name` to `v4`
6. When accepted, your content will be live on the website.

## Authoring Content

## Metadata

Each Markdown file can use the following metadata at the top.

```
---
title: title of content
draft: true or false (true will hide content)
tags: glossary, article, etc
---
```

Example simple glossary entry with complete valid Markdown file with metadata and content.

```
---
title: term
draft: false
tags: glossary
---

**term**

definition of the term
```

#### Markdown Cheatsheet

View a cheat sheet of Markdown formatting.
https://www.markdownguide.org/cheat-sheet/

### Content Architecture

Folders create expandable sections of categorized content (files). Feel free to propose new sections of content by adding a new folder

For now we have:
About - general info about the game
Roles - roles and role groups for playing the game
Sessions - for sharing data around individual sessions
