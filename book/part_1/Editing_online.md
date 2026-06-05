# Editing Your Book Online

The easiest way to make changes to your book is directly through the GitHub website, without installing anything on your computer. All you need is a browser and access to your repository.

## Opening a file for editing

Navigate to your repository on GitHub and click on the file you want to edit, for example `intro.md`. Once the file is open, click the **pencil icon** in the top-right corner of the file view. This opens the file in GitHub's built-in text editor, where you can start making changes straight away.

![This image shows where the pencil icon is.](https://github.com/MaastrichtUniversityPress/MUP_SETUP_INTRODUCTION/blob/main/book/part_1/images/pencil.png?raw=true)

When you are done editing, scroll down and commit your changes as described in the previous chapter. Your book will update automatically within a few minutes.

```{tip}
GitHub shows you a preview of how your page will look before you commit. Click the **Preview** tab at the top of the editor to check your formatting.
```

---

## Headings

Headings give your page structure and create the section titles your readers see. To create a heading, type a `#` symbol followed by a space and your title.

```
# This is a chapter title
## This is a section
### This is a subsection
```

The more `#` symbols you add, the smaller the heading. As a rule of thumb, use one `#` for the page title, `##` for main sections, and `###` for subsections within those.

---

## Bold and italic

To make text **bold**, wrap it in two asterisks on each side:

```
**This text will be bold**
```

To make text *italic*, wrap it in one asterisk on each side:

```
*This text will be italic*
```

You can also combine them for ***bold and italic*** using three asterisks on each side.

---

## Lists

For a **bullet list**, start each line with a `-` followed by a space:

```
- First item
- Second item
- Third item
```

For a **numbered list**, start each line with a number and a full stop:

```
1. First step
2. Second step
3. Third step
```

---

## Links

To add a clickable link, use the following format: the link text goes in square brackets, and the URL goes in round brackets directly after.

```
[Visit the MUP website](https://www.maastrichtuniversity.nl/about-um/faculties/university-library)
```

To link to another page within your own book, replace the URL with the filename of that page:

```
[Go to the introduction](intro.md)
```

---

## Images

To add an image to your page, you first need to upload it to the repository, potentially under a `images` folder. You can do this by navigating to the `images` folder and clicking **Add file** → **Upload files**.

Once the image is uploaded, you can place it in your text using the following format:

````
![Here you would put a general description of your image](https://github.com/MaastrichtUniversityPress/path-to-file?raw=true)
````

Replace `path-to-file` with the exact path of where your image is stored. Another way of retrieving this full path is by right-clicking on the image and clicking `Copy Image Link` or `Copy Image Address`.

```{tip}
Keep your image filenames simple and without spaces, for example `lecture-hall.png` rather than `Lecture Hall Photo Final.png`. Spaces in filenames can sometimes cause the image not to display correctly.
```

---

## Tables

In Markdown, a table is built using vertical bars `|` to separate columns and dashes `---` to mark the header row.

```
| Column 1      | Column 2      | Column 3      |
|---------------|---------------|---------------|
| Row 1, Cell 1 | Row 1, Cell 2 | Row 1, Cell 3 |
| Row 2, Cell 1 | Row 2, Cell 2 | Row 2, Cell 3 |
```

The first row becomes the header, displayed in bold. Each subsequent row is a new entry in the table. You do not need to align the columns perfectly, as GitHub will handle the formatting.

---

## What your edits look like end to end

To summarise, a typical session of updating your book would looks like this:

1. Open your repository on GitHub
2. Click on the `.md` file you want to change
3. Click the pencil icon to open the editor
4. Make your changes using the formatting above
5. Click **Preview** to check how it looks
6. Click **Commit changes**, and write a short description of what you did or changed. 

Your book will rebuild automatically, and your readers will see the updated version within a few minutes.