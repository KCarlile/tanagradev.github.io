---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Build
parent: Instructions
grand_parent: Docs
nav_order: 2
---

# Build
# **Build a Book Template**
A book template includes a book directory with the following:
- content directory: this will contain your book's content
- output directory: this will contain your book's rendered files (PDF, EPUB, HTML)
- outline markdown file: your book's outline used for generating file and directory structure
- metadata markdown file: information about your book

## **_tanagra build_**
First, you should navigate to the directory in which you would like to generate the book template. The build command will create a new directory within the *current working directory*.

```bash
$ cd Books/
```

The build command will prompt you for a book project name. You can enter a specific name or press enter to accept the auto-generated name.

```bash
$ tanagra build
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Building book template.
Checking current working directory (/Users/user/Books) for project...
Tanagra project not found in current directory: /Users/user/Books
What is a short name for your book project? This is not your title. [new_book_20200113-203331]
Magic Tricks for Dogs
Template creation completed.
/Users/user/Books/magic_tricks_for_dogs/content
/Users/user/Books/magic_tricks_for_dogs/output
/Users/user/Books/magic_tricks_for_dogs/metadata.md
/Users/user/Books/magic_tricks_for_dogs/outlne.md
```

In the output of the build command, you can see what was created:
- **content/:** a directory for storing your book's markdown files
- **output/:** a directory for storing your rendered books (PDF, EPUB, or HTML)
- **metadata.md:** a file for storing information about your project
- **outline.md:** a file in which you can create your book's outline for later conversion into a book structure in the `content/` directory

Your new Tanagra book project is now ready to begin working on your outline in the `outline.md` file.

## Next Steps
Now that your book template has been generated, you can populate your `metadata.md` and `outline.md` files. Once those are complete, you can [convert your outline to a book template](convert.html).
