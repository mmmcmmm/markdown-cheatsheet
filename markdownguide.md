# Table of Contents

- [Underline](#md )

- [Indent](#indent)

- [Center](#center)

- [Color](#color)

# Markdown websites {#md} 

--------

Website and languages use markdown

- **blot.io :** *blogging with a folder! Create website with **.md** files!!!*

- **jekyill:** turn md files into *html/css/Javascript* website!, **githubpages** uses jekyill as backend.

- **Ghost:** CMS with md support.

# Apps

-----

Here are some Markdown document authoring applications I recommend:

- Mac: MacDown, iA Writer, or Marked 2

- iOS / Android: iA Writer

- Windows: ghostwriter or Markdown Monster

- Linux: ReText or ghostwriter

- Web: Dillinger or StackEdit

-

# fenced code block

- - - 

```

{

  "firstName": "John",

  "lastName": "Smith",

  "age": 25

}

```

# Heading id {#custom-id}

` Heading id {#custom-id} `

Heading level 1

===============

```

Heading level 1

===============

```

Heading level 2

---------------

```

Heading level 2

---------------

```

# Adding Elements in Lists

> To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

* This is the first list item.

* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

1. First item

2. Second item

3. Third item

    - Indented item

    - Indented item

4. Fourth item

# Escaping Backticks

``Use `code` in your Markdown file.``

# Horizontal Rule Best Practices

Try to put a blank line before...

---

...and after a horizontal rule.

# Images

![The San Juan Mountains are beautiful!](https://mdg.imgix.net/assets/images/san-juan-mountains.jpg?auto=format&fit=clip&q=40&w=1080 "San Juan" )

Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](https://mdg.imgix.net/assets/images/shiprock.jpg?auto=format&fit=clip&q=40&w=1080 "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

The rendered output looks like this:

# Lightweight Markup Languages

There are several lightweight markup languages that are supersets of Markdown.

- CommonMark

- GitHub Flavored Markdown (GFM)

- Markdown Extra

- MultiMarkdown

- R Markdown

-

# Tables

| Syntax      | Description |

| ----------- | ----------- |

| Header      | Title       |

| Paragraph   | Text        |

| Paragraph   | Text        |

| Paragraph   | Text        |

# Alignment

| Syntax      | Description | Test Text     |

| :---        |    :----:   |          ---: |

| Header      | Title       | Here's this   |

| Paragraph   | Text        | And more      |

# Syntax Highlighting

To add syntax highlighting, specify a language next to the backticks before the fenced code block.

```json

{

  "firstName": "John",

  "lastName": "Smith",

  "age": 25

}

```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

# Heading IDs

### My Great Heading {#custom-id}

Adding custom IDs allows you to link directly to headings and modify them with CSS

First Term

: This is the definition of the first term.

Second Term

: This is one definition of the second term.

: This is another definition of the second term.

# Task Lists

- [x] Write the press release

- [ ] Update the website

- [ ] Contact the media

# Highlight

I need to highlight these ==very important words==.

I need to highlight these <mark>very important words</mark>.

# Underline

words <ins>will be underlined</ins>.

# center

<center>This text is centered.</center>

# color

<p style="color:blue">Make this text blue.</p>

# Comments

Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's

# Line Breaks Within Table Cells

| Syntax      | Description |

| ----------- | ----------- |

| Header      | Title |

| Paragraph   | First paragragh. <br><br> Second paragraph. |

# Css Style

6

The simplest way to add custom css styles is to use Pandoc attributes syntax (which can convert Markdown to html, pdf, pppt and more)

Heading Identifiers:
### Red text title {#identifier .red}

Fenced Code Attributes:
{.red .numberLines startFrom="1"}

Inline Code Attributes:
`red text`{.red}

Bracketed Spans:
[This is *some red text*]{.red}

Link Attributes:
![alt text](the.jpg){.center}


