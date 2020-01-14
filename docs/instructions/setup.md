---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Setup
parent: Instructions
grand_parent: Docs
has_children: true
has_toc: false
nav_order: 1
---

# Setup
## Prerequisites
- Python 3.7.5+
- Bash shell

## Installation
### Installing on Mac OS X
- Install [Homebrew](https://brew.sh/) package manager
  ```bash
  $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```
- Install [Pandoc](https://pandoc.org/)
   ```bash
   $ brew install pandoc
   ```
- For PDF conversion, install Mactex
   ```bash
   $ cask install mactex
   ```
   - Start a new terminal session after stalling mactex if you encounter errors generating PDFs.

- Install Tanagra
  The recommended location for installing Tanagra is `/usr/local/`, but you can install it anywhere that you like as long as you create the symbolic link to it in the next step.
   - [Download the zip file from the Tanagra repo](https://github.com/KCarlile/tanagra/archive/master.zip), save locally, and extract to (recommended location) `/usr/local/` so that the files are in `/usr/local/tanagra/...`
   - **...or...**
   - Clone the repo from GitHub:
     ```bash
     $ cd /usr/local
     $ git clone https://github.com/KCarlile/tanagra.git
     ```

- Create a symbolic link from `/usr/local/bin/tanagra` to the `scripts/tanagra.py` file
   ```bash
   $ ln -s /usr/local/tanagra/scripts/tanagra.py /usr/local/bin/tanagra
   ```

### Installing on Windows
**#TODO:** _Needs documentation._

### Installing on Linux
**#TODO:** _Needs documentation._

## Writing the Book
Tanagra presumes the author is using GitHub's [markdown format](https://guides.github.com/features/mastering-markdown/) for outline conversion, although the converter mechanism is more flexible.

## Next Steps
Now that you've setup Tanagra, you're ready to begin using it. Read the [instructions for more information](./).
