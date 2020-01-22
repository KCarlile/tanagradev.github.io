---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Compile
parent: Instructions
grand_parent: Docs
nav_order: 6
permalink: /docs/instructions/compile.html
---

# Compile
## Compile the Content Markdown into a Rendered Book
When you've completed writing your book or you'd like to generate a draft of the current state, you can use the `compile` command to convert the markdown and media in your `content` directory into a rendered e-book. Tanagra supports three different formats at this time: PDF, EPUB, HTML. Tanagra uses the [Pandoc universal document converter](https://pandoc.org/) behind the scenes to perform this conversion.


![Tanagra Workflow: Compile](/assets/images/tanagra-workflow-compile.png "Tanagra Workflow: Compile")

*The `tanagra compile book_format` command will convert the files in the `content/` directory into the specified `book_format` (PDF, EPUB, or HTML) seen outlined in purple.*

## **tagangra compile** [_book_format_]
The `compile` command accepts a book format of `pdf`, `epub`, or `html`. If you do not provide a book format, Tanagra will ask you which format you would like to use.

### With Book Format Parameter
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

### Without Book Format Parameter
```bash
$ tanagra compile
-------------------------------------
| Tanagra                           |
|   A markdown book pipeline tool   |
|   https://www.tanagra.dev/        |
-------------------------------------

Compiling markdown into book.
Checking current working directory (/Users/user/Books/magic_tricks_for_dogs) for project...
Please select the output format for your rendered book.
 [1] PDF
 [2] EPUB
 [3] HTML
...
```

## Rendered Book
When you've completed compiling your book, you can find it in the `output/` directory in your Tanagra project.

```bash
$ ls -l output/
total 152
-rw-r--r--  1 user  staff   5570 Jan 14 21:23 output.epub
-rw-r--r--  1 user  staff   1706 Jan 14 21:23 output.html
-rw-r--r--  1 user  staff  64753 Jan 14 21:21 output.pdf
```

## Next Steps
With your book complete and compiled into PDF, EPUB, or HTML, you're not ready to publish! Congratulations on your completed book! :)
