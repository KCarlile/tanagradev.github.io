---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Outline
parent: Instructions
grand_parent: Docs
nav_order: 3
---

# Outline
## Create a Book Outline

Now that you've built your Tanagra book project, you're ready to begin creating your outline. When you first open your `outline.md` file found in the root of your project directory, you'll see something like this:

```markdown
# Table of Contents (Outline)

1. Part 0 - Part Title
   1. Chapter 0 - Chapter Title
      1. Section Title
         1. Subsection Title
      1. Section Title
         1. Subsection Title
   1. Chapter 1 - Chapter Title
      1. Section Title
         1. Subsection Title
      1. Section Title
         1. Subsection Title

1. Part 1 - Part Title
   1. Chapter 2 - Chapter Title
      1. Section Title
         1. Subsection Title
      1. Section Title
         1. Subsection Title
   1. Chapter 3 - Chapter Title
      1. Section Title
         1. Subsection Title
      1. Section Title
         1. Subsection Title
```

This is a sample outline to get you started. The outline you see above represents a logical book outline like this:

- *Part 0 - Part Title/*
   - **Chapter 0 - Chapter Title.md**
   ```
      # Chapter 0 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - **Chapter 1 - Chapter Title.md**
   ```
      # Chapter 1 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
- *Part 1 - Part Title/*
   - **Chapter 2 - Chapter Title.md**
   ```
      # Chapter 2 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - **Chapter 3 - Chapter Title.md**
   ```
      # Chapter 3 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```

You can now edit your `outline.md` file to reflect your desired book outline before converting the outline into a book directory and file structure.

## Outline Tips
- Always indent your ordered list markdown with increments of 3 spaces as is the Github Markdown convention.
- Always use the `1.` for each level in the order list hierarchies.
- Note that the depth of each layer in the hierarchy determines whether it's a part (directory), chapter (file), or section/subsection (heading).
- Currently, you must have at least one book part, so if you don't intend to have multiple parts, just make a part 0 and give it the title of your book.
- Try to get your outline as good as you can before you convert it to content. If you need to make changes, you will have to do them manually or re-generate the content directory which will overwrite your previous writing in your markdown files.
- You can name parts and chapters anything you want, but they will be compiled in alpha-numerical order, so you may wish to prefix with numbers.

## Next Steps
When your outline is complete, you can proceed to [convert it into content directories and file structure](convert.html).
