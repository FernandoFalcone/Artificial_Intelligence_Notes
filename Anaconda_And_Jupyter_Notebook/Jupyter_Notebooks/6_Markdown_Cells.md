# Markdown cells

As mentioned before, cells can also be used for text written in Markdown. Markdown is a formatting syntax that allows you to include links, style text as bold or italicized, and format code. As with code cells, you press **Shift + Enter** or **Control + Enter** to run the Markdown cell, where it will render the Markdown to formatted text. Including text allows you to write a narrative along side your code, as well as documenting your code and the thoughts that went into it.

You can find the [documentation here](https://daringfireball.net/projects/markdown/basics), but I'll provide a short primer.

***

### Headers

You can write headers using the pound/hash/octothorpe symbol # placed before the text. One # renders as an h1 header, two #s is an h2, and so on. Looks like this:

```
# Header 1
## Header 2
### Header 3
```

renders as

# Header 1
## Header 2
### Header 3

***

### Links

Linking in Markdown is done by enclosing text in square brackets and the URL in parentheses, like this [Udacity's home page](https://www.udacity.com) for a link to Udacity's home page.

***

### Emphasis

You can add emphasis through bold or italics with asterisks or underscores (* or _). For italics, wrap the text in one asterisk or underscore, _gelato_ or *gelato* renders as gelato.

Bold text uses two symbols, **aardvark** or __aardvark__ looks like aardvark.

Either asterisks or underscores are fine as long as you use the same symbol on both sides of the text.

***

### Code

There are two different ways to display code, inline with text and as a code block separated from the text. To format inline code, wrap the text in backticks. For example, `string.punctuation` renders as string.punctuation.

To create a code block, start a new line and wrap the text in three backticks

```
import requests
response = requests.get('https://www.udacity.com')
```

or indent each line of the code block with four spaces.

```
import requests
response = requests.get('https://www.udacity.com')
```

***

### Math expressions

You can create math expressions in Markdown cells using LaTeX symbols. Notebooks use MathJax to render the LaTeX symbols as math symbols. To start math mode, wrap the [LaTeX](https://www.latex-project.org/) in dollar signs **$y = mx + b$** for inline math. For a math block, use double dollar signs,

```
$$
y = \frac{a}{b+c}
$$
```

This is a really useful feature, so if you don't have experience with [LaTeX please read this primer](http://data-blog.udacity.com/posts/2016/10/latex-primer/) on using it to create math expressions.

<a href="https://s3.amazonaws.com/content.udacity-data.com/courses/ud1111/Markdown+cells.mp4" target="_blank"><img src="https://cdn1.iconfinder.com/data/icons/logotypes/32/youtube-512.png" width="240" height="180" border="10" /></a>

***

### Wrapping up

Here's a cheatsheet you can use as a reference for writing Markdown. My advice is to make use of the Markdown cells. Your notebooks will be much more readable compared to a bunch of code blocks.
