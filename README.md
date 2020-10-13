# Git and GitHub

In the first part of this lab, we will learn about Git and GitHub for managing projects.

## 1. Git

[Git](https://git-scm.com/) is software that you will install on your computer that helps manage versions of documents.  It is an example of **version control software**.  At this point some editors have version control built in (Google Docs, for example, allows you to click backwards in the history).

![git1](figs/git1.jpg)

Once installed, you will be able to create your own _repository_ (directory), add files, and tag versions.  You can have complete ownership over your repository, and is especially good if you have a long-term project and you may want to be able to go back to earlier versions (thesis, anyone??).  

![git2](figs/git2.jpg)

Git is a **command line tool**, so you will need to open a Terminal (Spyder has a terminal built in) and navigate to your repository.  You will tag versions of a file (for example, `file.py` above) by first adding the changed file:

```
git add file.py
```

This _stages the file for a commit_, which prepares git for tagging this version.  You can add multiple files to commit a bunch at once. Then, to commit that version, you write

```
git commit -m "informational message about the changes"
```

This tags all files that have been added with a version number, and you can always revisit these versions.
