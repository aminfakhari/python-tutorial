# Markdown Cheat Sheet

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax/) and [extended syntax](https://www.markdownguide.org/extended-syntax/).

# Basic Syntax:
All Markdown applications support these elements.

### Heading:

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

### Bold:

**bold text**

### Italic:

*italicized text*

### Blockquote:

> blockquote

### Ordered List:

1. First item
2. Second item
3. Third item

### Unordered List:

- First item
- Second item
- Third item

You can nest an unordered list in an ordered list, or vice versa.
1. First item
2. Second item
3. Third item
   - Indented item
   - Indented item
4. Fourth item

### Code:

`code`

### Horizontal Rule:

---

### Link:

[Markdown Guide](https://www.markdownguide.org)

### Image:

From a URL:

![alt text](https://www.markdownguide.org/assets/images/tux.png)

From a folder next to .md file:

![alt text](Figures/my_image.png)


### Line Breaks:
To create a line break, end a line with two or more spaces, and then type return.

## Extended Syntax:

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table:

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


### Fenced Code Block:

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote:

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.


### Strikethrough:

~~The world is flat.~~

### Task List:

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Highlight:

I need to highlight these ==very important words==.

### Subscript:

H~2~O

### Superscript:

X^2^

### LaTeX Formulas:

Euler's identity: $e^{i\pi} + 1 = 0$

Or for block math:
$$
\int_{-\infty}^\infty e^{-x^2} dx = \sqrt{\pi}
$$