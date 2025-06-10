[GitHub's page on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

This is how to make an achor  
[Go to Headers](#headers) | [Go to Lists](#lists)  | [Go to Emphasis](#emphasis) | [Go to Lists](#lists) | [Go to Links](#links)  | [Go to Images](#images) | [Go to Code Blocks](#code-blocks)  | [Go to Footnotes](#footnotes) | [Go to Tables](#tables)  | [Go to Blockquotes](#blockquotes) | [Go to Horizontal Rule](#horizontal-rule)  | [Go to YouTube Videos](#youtube-videos) | [Go to Themes](#themes) 


This is how you can aligne text (Headers).
<h1 align="center" id="headers">   HEADERS:  </h1>


# H1
## H2
This is how you can aligne text (text).
<p align="center">
Alternatively, you can use the below commands for H1 and H2, an underline-ish style:
</p>

Alt-H1
======

Alt-H2
------

More Sub Headers

### H3
#### H4
##### H5
###### H6


# EMPHASIS:

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

# Lists:

1. First ordered list item
2. Another item
   * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the 3 leading spaces.

   To have a line break without a paragraph, you will need to use two spaces at the end of the stopping line.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses


# Links:

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title for easy management within the code](https://www.google.com "Google's Homepage")

[I'm a reference-style link, which later gets refrenced as a variable between [ ]][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file using githubs directory](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions, similar to variables][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> You need either the repository's link or a full http link.

Some text to show that the reference links can follow later. See bellow the different ways to reference links.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

# Images:

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

The reference is declared below in the code (remember to allways have a whole new line below text and references, otherwise they can be considered as linebraks of the same text and not as their own thing

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

# CODE BLOCKS:
Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
# Footnotes:   
_not part of markdown specifically_

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

# Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

# Blockquotes  
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

# Horizontal Rule

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

# YouTube Videos

Here is a video also on how to make repositories of different extension (have multiple at once).

<a href="https://www.youtube.com/watch?v=RdZqWiYCQsg
" target="_blank"><img src="https://cplmakerlab.github.io/uploads/how-to-make-a-website-with-github-pages/website-example.png" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

# Themes
[Select a theme from any of these and update the _config.yml file "remote_theme" line with the applicable theme's code](https://pages.github.com/themes/)
