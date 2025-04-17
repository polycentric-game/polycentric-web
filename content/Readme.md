# Welcome to Polycentric

### A role-playing game of agreements

## How to Contribute

The knowledge commons is built on simple [markdown](https://www.markdownguide.org/cheat-sheet/) files and served as a website through [Quartz](https://quartz.jzhao.xyz/).

## Get Started

1. Download [Obsidian](https://obsidian.md/download)

   Obsidian provides a nice UI for authoring Markdown content.

2. Clone and setup the repo https://github.com/oovg/quartz

````
``` git clone https://github.com/oovg/quartz
``` cd quartz
``` yarn
``` yarn quartz build --serve
````

3. Open the /content folder as a vault in Obsidian
   Create and Edit content with files and folders within Obsidian
4. Request access to push your updates back to [Github](https://github.com/oovg/quartz).
5. Create a pull request from `your-branch-name` to `v4`
6. When accepted, your content will be live on the website.

## Authoring Content

## Metadata

Each Markdown file should have the following metadata at the top.

```
---
title: title of content
draft: true or false (true will hide content)
tags: glossary, article, etc
---
```

Example simple glossary entry valid full Markdown file with metadata and content.

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

For now we simply have a Glossary and a Reading Room sections for content.

**Glossary:** Create new files, or edit existing ones in the "Glossary" folder
**Reading Room:** Add markdown versions of relevant articles, papers, and essays in the "Reading Room" folder to add content here

Feel free to propose new sections of content.
