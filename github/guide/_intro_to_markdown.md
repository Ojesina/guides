# Markdown
Markdown is the simplest way to write HTML using simple plain text.  John Gruber created Markdown with  thee goal of creating a HTML-publishable syntax that could be written quickly while maintaining readability.

Below is a quick guide for writing markdown documents.

# Markdown's Formatting Syntax

## Headers, Paragraphs, Text-Emphasis
```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6 (same size as 5 but gray)
####### Header 7 (no longer a header)
Paragraph with **bolded text**, _italicized text_, and ~~strikethrough text~~

```

## Numbered and Unordered Lists
```markdown
###### Numbered List
1. List 1
2. List 2
82. List something else (will autocorrect to 3)
   1. Inner List 1
   2. Inner List 2
   37. Inner List 3 (will autocorrect to 3)

###### Unordered List
- Unorderd List 1
- Unorderd List 2
   - Inner unorderd list 1
   - Inner unorderd list 2
```

###### Numbered List
1. List 1
2. List 2
82. List something else (will autocorrect to 3)
   1. Inner List 1
   2. Inner List 2
   37. Inner List 3 (will autocorrect to 3)

###### Unordered List
- Unorderd List 1
- Unorderd List 2
   - Inner unorderd list 1
   - Inner unorderd list 2

## Links, References, and Images
```markdown

###### Links
Inline-style link [link-text](https://www.google.com)
reference-style link (where `unique-id` is a unique identifier for the referece)
> [go to google][unique-id]
> [View Earth][other-unique-id]
> [Life Checklist][another-unique-id]

[unique-id]: https://www.google.com
[other-unique-id]: https://zoom.earth/
[another-unique-id]: http://neal.fun/life-checklist/

###### Footnotes
This text is referenced with a footnote.[^1]
[^1]: Text you thought was important enough to force people to look at the bottom of the page

###### Images
![image-hover-label](https://www.gstatic.com/webp/gallery3/1_webp_a.sm.png)
```

###### Links
Inline-style link [link-text](https://www.google.com)

Reference-style link (where `unique-id` is a unique identifier for the referece)
> [go to google][unique-id]
> [View Earth][other-unique-id]
> [Life Checklist][another-unique-id]

[unique-id]: https://www.google.com
[other-unique-id]: https://zoom.earth/
[another-unique-id]: http://neal.fun/life-checklist/

###### Footnotes
This text is referenced with a footnote.[^1]
[^1]: Text you thought was important enough to force people to look at the bottom of the page

###### Images
![image-hover-label](https://www.gstatic.com/webp/gallery3/1_webp_a.sm.png)

## Blockquotes and inline code snippets
```markdown
> something you want in blockquotes

inline code snippet `var code = 1`

Fenced code block (language = bash in output)

    ```language
    ls -a ~
    ```
```

> something you want in blockquotes

inline code snippet `var code = 1`

Fenced code block

```bash
ls -a ~
```

## Tables and Horizontal Rule
```markdown
Table Header 1              | Table Header 2
----------------------------|-----------------------------
Content from cell 1         | Content from cell 2
Content in the first column | Content in the second column

Horizontal rule

---

Another way to make a horizontal rule

***
```

Table Header 1              | Table Header 2
----------------------------|-----------------------------
Content from cell 1         | Content from cell 2
Content in the first column | Content in the second column

Horizontal rule

---

Another way to make a horizontal rule

***
