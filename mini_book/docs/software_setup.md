---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(software_setup)=

# Overview of tools

We will be using the following tools in the course:

- **Course announcements**: Canvas

- **Questions on problem sets**: we will be using Slack for you to pose questions to the TAs outside of office hours. You can join the Slack using your @georgetown.edu email at this link: [Slack link](https://join.slack.com/t/ppol564datasc-sgo8936/shared_invite/zt-1e22ol7s6-_HQgOhIi6HpNo4x3JUo_Fw)
    
- **Locally-installed python (for shorthand: local python)**: eventually, you'll leave the course and Gerogetown and need to know how to use Python locally. So in addition to jhub, I'm asking you to install the necessary software to run things locally: Python 3.8+ via the Anaconda distribution system

- **Terminal/terminal emulator**: mainly for interfacing with Git/GitHub. See instructions below for installation.

- **Git/GitHub**: one of the course goals is to get you more familiar with using Git/GitHub for version control. Instructions are below and we'll have an in-class activity where you create your own repo and add me as a collaborator. 

- **LaTeX/Overleaf**: we'll be using the LaTeX typesetting software to (1) integrate writing and formulae, (2) more cleanly integrate figures into writeups. We'll be interacting with LaTeX through Overleaf, so please create an account at this link (can link to your Gerogetown email or general gmail/email if you want access over time): [https://www.overleaf.com/learn/how-to/Can_I_try_Overleaf_without_signing_up%3F](https://www.overleaf.com/learn/how-to/Can_I_try_Overleaf_without_signing_up%3F). 

We won't be using a non-online LaTeX editor, but you can find information on installing those by googling "how to install LaTeX" and some popular editors include TeXworks and LaTeXiT.


## Python (by first class session)

Please download Python 3.9+ (if compatible with your OS) or an earlier version if you have an older operating system through the Anaconda distribution system linked to below. 3.8+ rather than 3.7 is strongly preferred due to compatibility between pkl files

- Site to go to: [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)
- Click on the following button (shows Mac by default on my computer but you can install on Windows or Linux)

```{image} ../images/anaconda_downloadlink.png
:alt: local terminal example
:class: bg-primary mb-1
:width: 500px
:align: center
```

## Terminal/terminal emulator (by second class session)


**Why do I need this?** in the course, we’ll be reviewing basic "command line" syntax. Knowing this is needed for:

- *Interacting with GitHub*: while there are ways to interact with GitHub through the online user interface, GitHub’s full functionality depends on being able to interact with repositories (basic folders that store code) through the command line.

-  *Executing .py or .R scripts that take a long time to finish executing*: ideally, you should write code that is efficient (runs quickly). But sometimes, regardless of how efficient the code is, things take a long time to run or are better run on servers than on your laptop that likely has limited computing resources. This requires being able to execute code by telling your computer to run a script and sometimes feeding that script arguments to parse.

### Macs

Macs have a built in terminal (to access, go to: 1. Search -> 2. Terminal). Below's a screenshot of what mine looks like when I'm navigated to a particular directory (Dropbox and a folder called `optimizingschools_publicviews`):

```{image} ../images/local_terminal.png
:alt: local terminal example
:class: bg-primary mb-1
:width: 500px
:align: center
```


I recommend also using screen to be able to start long-running processes, detach from them while they are running, and re-attach when they’re done: [http://www.kinnetica.com/2011/05/29/using-screen-on-mac-os-x/](http://www.kinnetica.com/2011/05/29/using-screen-on-mac-os-x/)

Some people prefer tmux for that purpose.


### Windows

Windows computers have various "terminal emulators," or things that, like terminal on Mac, help you go from the normal operating system you see, that often involves clicking on different folders, to interacting with files and programs through Unix commands. 

A couple popular ones are:

- [https://cmder.net/](https://cmder.net/)
- [https://www.cygwin.com/](https://www.cygwin.com/): cygwin operates a bit weirdly when, upon first install, you need to check the packages that you want installed. I recommend checking screen.


## Git/GitHub (by second class session)

We'll go over more Git/GitHub instructions during the relevant class session. Before that session:

1. Install Git if it's not installed already: [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

2. Create a GitHub account if you don't have one already (any email and free subscription is fine): [https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account](https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account)

## Text editor (by second class session)

**Why do I need this?** for longer-running code, a workflow might be:

- Write and test the code on a small sample of data in an IDE like:
    - Jupyter notebook (in a python notebook, or .ipynb file) or
    -  Rstudio (in a Rmarkdown file, or .rmd file)

- Then, translate the code into script form that can be run all at once without having to execute each cell, so:

    - Converting a python file from .ipynb (notebook form) to .py (script form)
    - Converting an R file from .Rmd (rmarkdown form) to .R (script form)

For step two, the code can be opened in any basic text editor that comes standard on your machine (e.g., text editor on Macs). But it’s nice to have a more visually appealing text editor meant for code that highlights parts of the syntax (e.g., the start of a function) to more easily catch mistakes.

Options (definitely non-exhaustive!):

- [https://www.sublimetext.com/3](https://www.sublimetext.com/3)
- [https://atom.io/](https://atom.io/)
- [https://www.nano-editor.org/download.php](https://www.nano-editor.org/download.php)
- [http://aquamacs.org/](http://aquamacs.org/)

Text editors are also good for yaml files, which can be used to store things like passwords/credentials to access APIs. Here's an example of Sublime Text and a yaml file I have that has the table of contents for this QSS20 course website:

```{image} ../images/sublime_example.png
:alt: sublime example
:class: bg-primary mb-1
:width: 300px
:align: center
```


