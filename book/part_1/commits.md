# Your Book is Always Safe: Commit History

When you commit a change 

1. **A snapshot of your book is saved.** The power of Github is the fact that it stores all of these snapshots after each commit, meaning you can open any of these versions whenever you want, that is why it is a good habit to commit often. 

```{tip}
**Want to go further?** GitHub also supports something called **branches**. Imagine your book is finished and published, but you want to start working on a new chapter without affecting what your readers currently see. A branch lets you do exactly that, it's like a parallel copy of your book where you can make changes freely, and only merge them into the live version when you're ready. More on this in the advanced guide later on!
```

2. **Your live book updates automatically.** TeachBooks detects the new commit and rebuilds your book, so your readers will see the changes within a few minutes. This is done under the `Actions` - `All workflows` - `call-deploy-work`, where it shows you a descriptive summary of the build, such as if there were any errors in the whole process and where the book was released online. 



## Viewing your commit history

You can browse every change ever made to your book by clicking the **"Commits"** button on your repository's main page, highlighted in yellow in the image below. Each entry in the list represents a saved snapshot of your book at that point in time, along with the message you wrote when you committed.

```{figure} images/commit.png
:width: 80%

This image shows the Commits button on your repository's main page.
```

## Recovering an older version

If something goes wrong, maybe you accidentally deleted a section or a change broke the layout of your book, you can always go back to the previous version. This is because every commit is a saved snapshot, you can also always contact the MUP team and they can help you restore your book to any earlier version.

```{tip}
This is one of the biggest advantages of working with GitHub. You never have to worry about losing your work or making an irreversible mistake, every version of your book is always there.
```