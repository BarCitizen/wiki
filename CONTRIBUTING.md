# Contributing to Our Wiki

Welcome! This guide will help you create and edit mkdocs wiki pages, even if you're not technical. Think of this as a simple recipe for adding content to our documentation.

# What You Need to Know

Our wiki is built using MkDocs, which turns simple text files into beautiful web pages. You don't need to know any programming - just how to write and format text with markdown.

Our wiki supports multiple languages! people around the world will be able read the documentation in their preferred language once the english version is translated to their preferred language.

We will talk more about this in a later section.


# Best Practices / Wiki Style Guides

Please follow these to keep the wiki organized and properly structured!

- Keep Image assets in docs/assets. This will allow us properly share images across I8n localized wiki pages.
- Keep the folder and filenames the same across all languages - only the content inside files should be translated. This will reduce overhead administration burden 
- Keep the same folder structure as the EN language for other languages   
- Use lowercase and hyphens for filenames

<br>

# Example Wiki Page
### Step 1: Create Your File

Wiki pages are just text files with a .md extension (which stands for Markdown). Here's how to create one:

- Go to the docs folder in the project
- Go into the language folder you are writing the wiki page for
- Create a new file with a descriptive name, like getting-started.md


### Step 2: Write Your Content

Open your new file and start writing! 

Here's a simple template:

```

# Wiki Page Title

A brief introduction to what this page covers.

## First Section

Write your content here. You can write normally, just like in an email.

### Subsection

Break up your content with headings to make it easier to read.

## Another Section

Keep adding sections as needed.

## Example Image
![alternate text if image doesnt load or for screen readers](./docs/assets/Bar_Citizen_Logo_White.svg)

```

Any markdown content should be supported. to see all options check out https://www.geeksforgeeks.org/html/markdown-cheat-sheet/

### Step 3: Translate your Content

Translating your page is straightforward and simple.

Each language has its own folder inside the docs folder like this:

```
assets/
docs/
  en/           # English pages
  es/           # Spanish pages
  fr/           # French pages
  de/           # German pages
```


You can simply copy your page and paste it into one of the the language folders above, translate the content in that page and thats it! the rest is handled for you.

If you can't translate to all languages right away, that's okay! Create the English version first, and translations can come later


# Testing/Submitting Your Changes

Before submitting your changes, you can preview them locally:

- Install mkdocs via the README file
- Run 'mkdocs serve' command in your terminal 
- Open your browser to http://localhost:8000
- Check that your page looks good and all links work!

Afterwards please open a pull request to this repository with your changes. Ensure you label which language it is for like so:

```
[EN] Adding documentation on how to become a coordinator
```
or

```
[ES] Adding Spanish Translation for coordinator wiki pages
```

---

Thank you for contributing to our wiki! Every page you add helps our community.