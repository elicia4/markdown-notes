# Markdown in 30 minutes

Notes on the video by Faraday Academy: https://youtu.be/bTVIMt3XllM

### What is Markdown
---

Markdown is a simplified markup language that is used for formatting text. It
gives you a way to format text so that it can be converted to HTML. It was
originally described as a text-to-HTML formatting tool.

### Why & Where to use it
---

Markdown is a lot easier to learn, read and use than HTML. It is one of the 
most popular ways for formatting blogposts, documentation, and note-taking, as
well as Python notebooks (Jupyter notebooks as Markdown documents). You can
create tables and flowcharts in MD, as well as write entire research papers and
books in this MD syntax.

There are different flavors of Markdown, there are minor differences between
them which came about because of flawed specificatoins at the beginning of the
development of Markdown. People came up with ways to fill up the gaps on their
own. For example, there is GitHub Flavored Markdown, or GFM, which offers a few
additional features to Markdown on their platform.

Some of the most popular apps for note-taking with MD are:
- Bear App
- Standard Notes
- Joplin
- Obsidian  

For blogs, a platform called Ghost may come in handy, that also gives you an 
admin interface to write your blogs in MD. 

Some forums also utilize MD, such as the freeCodeCamp forum and many other
development forums. It's also popular in Jamstack. 

### Basics of Syntax
---

*This will not cover what is already covered in the [quick
guide](md-in-1-min.md).*

A good way to create a table of contents:

``**Table of Contents:**``

It will be displayed like so:

>**Table of Contents:**

You can use `~~` to strike through text:

>`~~striken~~` == ~~striken~~

This is useful for lists.  

You can also have italic text in the middle of bold
text, for example `**There is *italic* text here**`
renders as:  

>**There is *italic* text here**

You can nest items in lists:

1. 123
    1. 123
    1. 456
1. 456  

The fact that you don't have to identify each item in a list with a correct
index is useful for cases when you need to quickly reorder a list, since you
don't have to change the indices manually for them to be in a correct order.
Try it out:

1. I am first 
1. I want to be third
1. I want to be second  

You can indicate which language of you code you use inside of you code blocks
to make your highlighting better:

``` py
import rand-lib
class Random:
    number = value
    values = (1, 2, 3, 4)
```

To add horizontal lines, use `---`:

---

A thin horizontal line is also added under the H1 header on many platforms.

You can create multiline quotes, you can also use HTML with MD, for example:

```
>Lorem ipsum dolor sit amet, consectetur adipiscing elit,
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Et malesuada
fames ac turpis egestas maecenas.
>
> -- &lt;cite>Bob Ross&lt/cite>
```

Renders as:

>Lorem ipsum dolor sit amet, consectetur adipiscing elit,
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Et malesuada
fames ac turpis egestas maecenas.
>
> -- <cite>Bob Ross</cite>

You can quote HTML tags (the problem is with the 'less that sign', or `<`) by
using either backticks (\`<\`) or `&lt;`, which will render as &lt;.

For unordered lists, `-` is more widely supported than `*`.

### Advanced cases & libraries
---

