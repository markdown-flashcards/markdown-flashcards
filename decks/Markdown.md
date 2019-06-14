# Markdown
Markdown is a lightweight markup language with plain text formatting syntax.

## Paragraphs

---
Paragraph

Second paragraph

?

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines (containing nothing but spaces or tabs).

```
First paragraph

Second paragraph
```

---

Long paragraphs.

Lorem ipsum dolor sit amet, consectetur
adipiscing elit, sed do eiusmod tempor 
incididunt ut labore et dolore magna 
aliqua.

?

Long paragraphs can be split into multiple lines provided there is no blank line between them.

```md
Lorem ipsum dolor sit amet, consectetur↵
adipiscing elit, sed do eiusmod tempor↵
incididunt ut labore et dolore magna↵
aliqua.
```

---

Paragraph with line breaks

First line  
Second line\
Third line

?

To break a line it should be followed by two or more spaces or be terminated with a backslash character '`\`'.

```md
First line with two trailing spaces..↵
Second line with backslash\↵
Third line
```

---


## Headers 

---

Headers (e.g. title, section, subsection) with prefix style.

?

```md
# H1 (title)
## H2 (section)
### H3 (sub-section)
#### H4 (sub-sub-section)
##### H5
###### H6
```

---

Headers (e.g. title, section, subsection) with underline style.

?

```md
H1 (title)
==========

H2 (section)
------------
```

---

## Fonts

---

*Italics font*

? 

Single asterisks or underscores
```md
*Italics font*
_Italics font_
```

---

**Bold font style**

?

Double asterisks or underscores
```md
**Bold font**
__Bold font__
```

---

***Italics and bold font***

? 

Triple asterisks or any valid combination of asterisks and underscores
```md
***Italics and boldfont***
**_Italics and boldfont_**
__*Italics and boldfont*__
```

---

~~Strikethrough font~~

?

Double tildes
```md
~~Strikethrough font~~
```

---

## Lists

---

Ordered list
1. First item
2. Second item

?

Start each item with a digit (0-9), followed by either a '`.`' character or a '`)`' character.
```md
1. First item
2. Second item

1) First item
2) Second item
```

---

Ordered list with long paragraphs.
1. First sentence of the first paragraph.
   Second sentence of the first paragraph.

   First sentence of the second paragraph.

2. Second item

?

Align all sentences with the beginning of first one by indenting them with 3 spaces. You can also use a single tab instead.
```md
1. First sentence of the first paragrap.
   Second sentence.

   Second paragrap.

2. Second item
```

---

Ordered list with sub-list
1. First item
   1. First sub-item
2. Second item
	1. Second sub-item

?

Align sub-list with the beginning one the parent item by indenting it with 3 spaces. You can also use a single tab instead.
```md
1. First item
   1. First sub-item (spaces)
2. Second item
	1. Second sub-item (tab)
```

---

Mixed ordered and bullet lists
1. First ordered item
   - First bullet list sub-item
   - Second bullet list sub-item
2. Second ordered item

?

Align sub-list with the beginning one the parent item by indenting it with 3 spaces. You can also use a single tab instead.
```md
1. First ordered item
   - First unordered sub-item
   - Second unordered sub-item
2. Second ordered item
```

---

Bullet list
- First item
- Second item

?

Start each line with a '`-`', '`*`', or '`+`' character.

```md
- First item
- Second item

* First item
* Second item

+ First item
+ Second item
```

---

Bullet list with long paragraphs.

- First sentence of the first paragraph.
  Second sentence of the first paragraph.

  First sentence of the second paragraph.

- Second item

?

Indent all the lines with 2 spaces or a single tab.
```md
- First sentence of the first paragraph.
  Second sentence of the first paragraph.

  First sentence of the second paragraph.

- Second item
```

---

Bullet list with sub-list
- First item
  - First sub-item
- Second item
	- Second sub-item

?

Indent sub-list with 2-4 spaces or single tab.
```md
- First item
  - First sub-item (spaces)
- Second item
	- Second sub-item (tab)
```

---

## Links

---

Inline-style [link](https://www.google.com)

?

```md
Inline-style [link](https://www.google.com)
```

---

Inline-style [link with title (hover over)](https://www.google.com "Google's Homepage")

?

```md
Inline-style [link with title (hover over)](https://www.google.com "Google's Homepage")
```

---

Inline-style [link to a file in the same folder](Markdown.md)

?

```md
Inline-style [link to a file in the same folder](Markdown.md)
```

---


Inline-style [link to a file in the parent folder](../Readme.md)

?

```md
Inline-style [link to a file in the parent folder](../Readme.md)
```

---


Inline-style [link to a file in the child folder](./child/Readme.md)

?

```md
Inline-style [link to a file in the child folder](./child/Readme.md)
```

---


Reference-style [text link][case-insensitive reference text]

[case-insensitive reference text]: https://www.google.com

?

```md
Reference-style [text link][case-insensitive reference text]

[case-insensitive reference text]: https://www.google.com

```

---

Reference-style [number link][1]

[1]: https://www.google.com

?

```md
Reference-style [number link][1]

[1]: https://www.google.com
```

---

Reference-style verbatim [text link]

[text link]: https://www.google.com

?

```md
Reference-style verbatim [text link]

[text link]: https://www.google.com
```

---

Reference-style verbatim number link [2]

[2]: https://www.google.com

?

```md
Reference-style verbatim number link [2]

[2]: https://www.google.com
```

## Image

---

Inline-style image by a full URL  
![](https://www.iconfinder.com/icons/298823/download/png/48)

?

```md
Inline-style image by a full URL  
![](https://www.iconfinder.com/icons/298823/download/png/48)
```

---

Inline-style image in the same folder  
![](logo_48.png)

?

```md
Inline-style image in the same folder  
![](logo_48.png)
```

---

Inline-style image in the parent folder  
![](../logo_48.png)

?

```md
Inline-style image in the parent folder  
![](../logo_48.png)
```

---

Inline-style image in the child folder  
![](./child/logo_48.png)

?

```md
Inline-style image in the child folder  
![](./child/logo_48.png)
```

---


Inline-style image with alternative text  
![alternative text](logo_48.png)

?

```md
Inline-style image with alternative text  
![alternative text](logo_48.png)
```

---

Inline-style image with title (hover over)  
![](logo_48.png "Markdown Logo")

?

```md
Inline-style image with title (hover over)  
![](logo_48.png "Markdown Logo")
```

---

Reference-style image  
![][logo_local]
![][logo_url]

[logo_local]: logo_48.png
[logo_url]: https://www.iconfinder.com/icons/298823/download/png/48

?

```md
Reference-style image  
![][logo_local]
![][logo_url]

[logo_local]: logo_48.png
[logo_url]: https://www.iconfinder.com/icons/298823/download/png/48
```

---

## Code
Code blocks are part of the core Markdown spec, but syntax highlighting is only supported in GFM.


---

Inline `code` in a sentence.

?

Surround inline code with back-tick characters '`'.
``` md
Inline `code` in a sentence.
```

---

Code block

```
code block
```

?

 Code blocks should be fenced by lines with three back-ticks '```' or indented with four spaces. First option has advantage as it supports syntax highlighting.

    ```
    code block fenced by lines with three back-ticks
    ```

```
....code block indented with four spaces
```

---

Syntax highlighting 

```python
print("Syntax highlighting in Python")
```

?

Add the language idetifier after opening back-ticks.

    ```python
    print("Syntax highlighting in Python")
    ```

---

## Tables
Tables aren't part of the core Markdown spec, but they are part of GFM.

---
Table

| Column 1 | Column 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |

? 

Table consists of header and delimiter row followed by rows lines. It can be written in a way which makes it readable even in the plain text.

```
| Column 1 | Column 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

Some elements can be omitted. Required elements include inner pipe '`|`' characters and second line to separate table headers. The following table is a minimalistic example which produces the same result.

```
Column 1 | Column 2
-|-
Cell 1 | Cell 2
Cell 3 | Cell 4
```

---

Table with left-aligned column.

| Left aligned column |
| :------------------ |
| Cell 1              |
| Cell 2              |

?

All the columns are aligned left by default, but optionally you can make it explicit by adding a leading colon '`| :---`' in the delimiter row.

```md
| Left aligned column |
| :------------------ |
| Cell 1              |
| Cell 2              |
```

---

Table with right-aligned column.

| Right aligned column |
| -------------------: |
| Cell 1               |
| Cell 2               |

?

For right alignment add trailing colon '`---: |`' in the delimiter row.


```md
| Right aligned column |
| -------------------: |
| Cell 1               |
| Cell 2               |
```

---

Table with center-aligned column.

| Center aligned column |
| :-------------------: |
| Cell 1                |
| Cell 2                |

?

For center alignment add both leading and trailing colons '`| :---: |`' in the delimiter row.


```md
| Center aligned column |
| :-------------------: |
| Cell 1                |
| Cell 2                |
```

---

## Quotes

---

Quote

> Quote

?

```
> Quote
```

---

Quote with multiple paragraphs

> First sentence of the first paragraph.
> Second sentence of the quote.
>
> First sentence of the second paragraph.

?

```
> First sentence of the first paragraph.
> Second sentence of the quote.
>
> First sentence of the second paragraph.
```

---

Long quote.

> First sentence of the quote.
Second sentence of the quote.

?

Once quote is started character '`>`' becomes optional.

```
> First sentence of the quote.
Second sentence of the quote.
```


---


Nested quote

> Quote level 1
>> Quote level 2
>>> Quote level 3

?

Quotes can be nested by adding more character '`>`' to the beginning of the line.

```
> Quote level 1
>> Quote level 2
>>> Quote level 3
```

## Thematic breaks

---
Horizontal rule.

?

Horizontal rules are formed by a sequence of three or more matching '`-`', '`_`', or '`*`' characters.

```
---
------

***
******

___
______
```

---

## Math
Math equations are not part of the core Markdown, but many editors do support them. For Visual Studio Code it is necessary to install extension to enable this functionality (e.g. [Markdown+Math](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath)).

Math equations can be constructed using LaTeX syntax (e.g. [LaTeX/Mathematics](https://en.wikibooks.org/wiki/LaTeX/Mathematics)).

---

Inline math expression: $c = \sqrt{a^2 + b^2}$

?

Inline math expressions can be formatted by surrounding them with '`$`' characters.

```
Inline math expression: $c = \sqrt{a^2 + b^2}$
```

---

Block with math equation

$$ 
c = \sqrt{a^2 + b^2}
$$

?

Math equation blocks should be surrounded with two dollar '`$$`' signs. You can write them in multiple (fenced style) a single line.
```md
$$
c = \sqrt{a^2 + b^2}
$$
```
```md
$$ c = \sqrt{a^2 + b^2} $$
```

---

Block with math equation and numbering

$$
c = \sqrt{a^2 + b^2}
$$ (1)

?

To add number to the math block add number in parentheses to the closing mark ('`$$ (1)`').
```md
$$
c = \sqrt{a^2 + b^2}
$$ (1)
```

---


## Inline HTML
While not so common, some editors allow for raw HTML in your Markdown.

---

Inline HTML

<dl>
  <dt>HTML definition list</dt>
  <dd>In a definition list, each list item contains two entries: a term and a description.</dd>
</dl>

?

```html
<dl>
  <dt>HTML definition list</dt>
  <dd>In a definition list, each list item contains
    two entries: a term and a description.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Once in HTML you cannot use Markdown syntax 
    (e.g. *not*, **very**). Instead you have to rely 
    entirely on <strong>HTML tags</strong>.</dd>
</dl>
```

---