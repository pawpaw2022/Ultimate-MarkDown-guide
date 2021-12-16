<!-- Basic Syntax on MarkDown Language -->

<!-- Tips: To preview your md,
install Auto-Open Md Preview Extension in VScode -->

<!-- Headings -->

# Heading 1

## Heading 2

### Heading 3

<!-- Italics -->

_This Text_ is italic

_This Text_ is also italic

<!-- Bold -->

**This text** is Bold

**This text** is Bold

<!-- Strikethrough -->

~~This text~~ is strikethrough

<!-- Note: add "\" to show the actual symbol -->

\* This text \* has asterisks

<!-- Horizontal Bar -->

---

---

<!-- Blockquote -->

> This is a quote

<!-- Links -->

[Paul's GitHub Page](https://github.com/Paul-l-sining)

[Paul's GitHub Page](https://github.com/Paul-l-sining "Paul's GitHub Page") <!-- Title the link -->

<!-- UL -->

- Item 1
- Item 2
  - Nested Item 1
    - Nested Item 2

<!-- OL -->

1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->

`<p> This is a paragraph</p>`

<!-- Images -->

![A Nice Wallpaper](https://img0.baidu.com/it/u=914661082,2026368281&fm=26&fmt=auto&gp=0.jpg)

<!-- Github Markdown -->

<!-- Code Blocks -->

```bash
  npm install

  npm start
```

```java
public static void main(String args[]){
    // Testing Java code:
    System.out.println("Hello, Java")
}
```

```python
def main():
    # Testing python code:
    print("Hello, Python")
```

<!-- Tables -->

| Name      | Email           |
| --------- | --------------- |
| Paul Lu   | plu@gmail.com   |
| Lynn Yang | lyang@gmail.com |

> Tips: Creating tables with hyphens and pipes can be tedious. To speed up the process, try using the [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables). Build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file.

<!-- Task Lists -->

- [x] Task 1
- [x] Task 2
- [ ] Task 3

---

## Additional Bundles

### Definition Lists

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

### Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

### Color Code

Not specifying language, Plain text:

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Specifying language, highlights:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Hyperlinks to Heading

(Note: all lowercases & replace `space` with `-` inside parentheses)

[Additional Bundles](#additional-bundles)

### Emoji

> Note: `Markdown Preview Enhanced` extension needed.

That is so funny! :joy:
Gone camping! :tent: Be back soon. :see_no_evil:

> Note: You can use this [list of emoji shortcodes](https://gist.github.com/rxaviers/7360908), but keep in mind that emoji shortcodes vary from application to application. Refer to your Markdown application's documentation for more information.

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^
