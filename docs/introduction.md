---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Overview
parent: Docs
nav_order: 1
---

# Overview
Tanagra is a documentation pipeline tool for building a template for a markdown-based book, generating a directory and file structure based on an outline, and then converting markdown files into HTML, PDF, and EPUB books using [Pandoc](https://pandoc.org/).

## Markdown Book Pipelines Workflow
1. **Decide on a topic for your book.** Tangara cannot help you with this step. :)
1. **Create a book template using Tanagra.** This will generate a book content directory, an `outline.md` file,
1. **Populate your book's `outline.md` file.** Using markdown, populate the `outline.md` file generated in step 1 above. See the outline structure below.
1. **Convert your book's `outline.md` file into a book directory hierarchy and markdown files.** This step will create a hierarchy of directories (per part and chapter) and markdown files (per chapter) with sections and subsections stubbed out in the markdown files.
1. **Write your book in the markdown files.** Using the chapter markdown files, populate your book within the files and headings populated in the previous step.
1. **Generate the final output file(s) for your book.** Once you have completed writing your book in the markdown files, you can generate a PDF, EPUB, or HTML version of your book.
1. **Publish your book.** Tanagra cannot help you with this step either. Upload, email, or do whatever you need to do with your generated book to deliver it to your audience.

## FAQ
### Why should I write my book in markdown?
By writing in Markdown files, you can easily use version control for your files _and_ you can still use text markup (headings, bold, italic, code, etc.).

### Why would I want to write the outline first?
For non-fiction and technical books, having a thorough outline can help keep your writing focused on your topic and ensure that you cover the necessary subtopics.

### Why would I want to use separate directories and files for my chapters?
Breaking up your book into small chunks can help keep you focused on chunks that you can tackle without being overwhelmed.

### Who asked for this project? It seems like a duplicate of {some_project}.
No one asked for this and it might be similar to something else out there, but it seemed like a fun idea at the time. :)

### Why use Python for the scripts?
Python is a cool language and the founder of the Tanagra project was interested in using Python on a project at the time of inception.
