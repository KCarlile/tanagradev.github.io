---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Instructions
parent: Docs
has_children: true
has_toc: false
nav_order: 2
permalink: /docs/instructions/
---

# User Instructions
The following instructions are calling the various commands for creating a book using the Tanagra main script.

In general, the process to use Tanagra is as follows:
1. **Setup Tanagra on your local computer.** See [Setup](setup.html).
1. **Build a book template.** See [Build a Book Template](build.html).
1. **Populate the `outline.md` file**
1. **Convert the completed outline file into a directory and file structure.** See [Convert an Outline into a Directory and File Structure](convert.html).
1. **Write the content of your book in the generated files of the `content/` directory and add any media files to each book part's media Directory.**
1. **Compile markdown into a rendered book.** See [Compile Markdown into a Rendered Book](compile.html).

## Calling Tanagra
There are two ways to call Tanagra: interactive mode or command mode.

### Interactive
In interactive mode, you just call Tanagra and it will prompt you for what you want to do:
```bash
$ tanagra
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Please enter a number to specify a command.
 [1] Build a new book template
 [2] Convert outline into file structure
 [3] Compile markdown files and media into a book
 [4] Exit Tanagra
```

In command mode, you provide the command and bypass Tanagra's prompts:

### Build
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
What is a short name for your book project? This is not your title. [new_book_20200113-201753]
```

### Convert
```bash
$ tanagra convert
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Converting outline into file structure.
Checking current working directory (/Users/user/Books/magic_tricks_for_dogs) for project...
...
```


### Compile
```bash
$ tanagra compile pdf
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Compiling markdown into book.
Checking current working directory (/Users/user/Books/magic_tricks_for_dogs) for project...
...
```

Alternately, you can call compile command in semi-interactive mode:

```bash
$ tanagra compile
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Compiling markdown into book.
Checking current working directory (/Users/user/Books/magic_tricks_for_dogs) for project...
Warning: Content directory is not empty.
Please select the output format for your rendered book.
 [1] PDF
 [2] EPUB
 [3] HTML
...
```

## More Information
For more details on each step in the process of building a book with Tanagra, please view these sections:
- [Setup](setup.html)
- [Build](build.html)
- [Outline](outline.html)
- [Convert](convert.html)
- [Content](content.html)
- [Compile](compile.html)
