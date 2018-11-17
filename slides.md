---
title: "First Notebook War"
author: "Martin Skarzynski"
date: "2018-11-17"
---

# About me

# About this talk

- The title: inspired by [a tweet](https://twitter.com/pgbovine/status/1034626381735317504)
- Focus: [Jupyter notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)

![tweet]()
[Phil Guo (@pgbovine)](https://twitter.com/pgbovine)
# Previous conflicts

- Spaces versus Tabs
- Emacs versus Vim

![Silicon Valley GIF]()

# Spaces versus Tabs

- Code editor setup: Tab = 4 spaces
- GNU Make requires tabs!
- Use spaces, get paid more!

![StackOverflow chart]()

# Notebooks

[Jupyter notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)
- are data science tools
- built on IPython by [Fernando Perez (@fperez)](https://twitter.com/fperez)
- combine [Markdown](https://www.markdownguide.org/) text, code, and output
- help data scientists communicate goals, methods, and results
- used in
    - [academia](https://www.oreilly.com/ideas/all-the-cool-kids-are-doing-it-maybe-we-should-too)
    - [Amazon](https://www.oreilly.com/ideas/machine-learning-and-ai-technologies-and-platforms-at-aws)
    - [Netflix](https://medium.com/netflix-techblog/scheduling-notebooks-348e6c14cfd6)
    - [PayPal](https://medium.com/paypal-engineering/paypal-notebooks-powered-by-jupyter-fd0067bd00b0)



# Joel doesn't like notebooks

- ["I Don't Like Notebooks" by Joel Grus at Jupytercon 2018](https://conferences.oreilly.com/jupyter/jup-ny/public/schedule/detail/68282)
- Modularity and Reusability

![Lego GIF]()

## or the down arrow in slides

![The scream]()

# Tim likes notebooks

![Brevity Burn]()

# DataFramed podcast
- Podcast by Hugo Bowne Andersen

# JupyterLab
- text editor and REPL

# Yihui

- [Blog post](https://yihui.name/en/2018/09/notebook-war/)
- [R notebooks](https://rmarkdown.rstudio.com/r_notebooks)
- these slides are made with R markdown!

@xieyihui

# Why use notebooks

- [Literate programming](http://www.literateprogramming.com/)
- Rendered by GitHub and nbviewer
- Google [colab](https://colab.research.google.com/)
- [Kaggle kernels](https://towardsdatascience.com/introduction-to-kaggle-kernels-2ad754ebf77)
- [Binder]()

@jakevplas

# Notebook tools

1. version control tool for notebooks - [nbdime]()
2. work with Jupyter notebooks, R markdown, and Julia, Python, and R scripts using [JupyText](https://github.com/mwouts/jupytext)
3. configure Jupyter Notebooks to run on markdown files with [notedown](https://github.com/aaren/notedown)
4. create and run Jupyter and R notebooks from scripts and markdown files with [nbless](https://github.com/marskar/nbless)

@mwouts 

# Write modules!

- Imports
    1. Standard Library
    2. Third Party
    3. User Defined
- Definitions
    - Classes
    - Functions
- Type Hints (Steven Lott's tutorial yesterday)
- Docstrings (with examples)
- `if __name__ == '__main__':`
- Function call(s), e.g. `doctest.testmod(verbose=True)`

# Thanks for listening!
