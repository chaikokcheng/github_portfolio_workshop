# How to Build an Awesome GitHub Portfolio (Profile README)

---

## 0. Markdown Crash Course

Your GitHub README is written in **Markdown** — a lightweight syntax that turns plain text into formatted content. Here's everything you need to know.

### Headings

Use `#` symbols. More `#` = smaller heading.

**You write:**

```markdown
# Heading 1 (largest)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 (smallest)
```

**It renders as:**

> # Heading 1 (largest)
> ## Heading 2
> ### Heading 3
> #### Heading 4
> ##### Heading 5
> ###### Heading 6 (smallest)

---

### Text Formatting

**You write:**

```markdown
**bold text**
*italic text*
***bold and italic***
~~strikethrough~~
`inline code`
```

**It renders as:**

> **bold text**
>
> *italic text*
>
> ***bold and italic***
>
> ~~strikethrough~~
>
> `inline code`

---

### Links

**You write:**

```markdown
[Click here to visit Google](https://google.com)
```

**It renders as:**

> [Click here to visit Google](https://google.com)

---

### Images

**You write:**

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

**It renders as:**

> ![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

The `!` before the brackets is what turns a link into an image.

---

### Lists

**Unordered list — you write:**

```markdown
- Item one
- Item two
  - Nested item (indent with 2 spaces)
  - Another nested item
```

**It renders as:**

> - Item one
> - Item two
>   - Nested item (indent with 2 spaces)
>   - Another nested item

**Ordered list — you write:**

```markdown
1. First step
2. Second step
3. Third step
```

**It renders as:**

> 1. First step
> 2. Second step
> 3. Third step

---

### Blockquotes

**You write:**

```markdown
> This is a blockquote.
> Great for callouts or tips.
```

**It renders as:**

> This is a blockquote.
> Great for callouts or tips.

You can nest blockquotes too:

**You write:**

```markdown
> Level 1 quote
>> Level 2 nested quote
```

**It renders as:**

> Level 1 quote
>> Level 2 nested quote

---

### Code Blocks

Wrap code in triple backticks. Add a language name for syntax highlighting.

**You write:**

````markdown
```javascript
function greet(name) {
  return `Hello, ${name}!`;
}
```
````

**It renders as:**

> ```javascript
> function greet(name) {
>   return `Hello, ${name}!`;
> }
> ```

Common languages: `javascript`, `python`, `java`, `bash`, `html`, `css`, `typescript`, `rust`, `go`

---

### Tables

**You write:**

```markdown
| Name    | Role       | Language   |
|---------|------------|------------|
| Alice   | Frontend   | TypeScript |
| Bob     | Backend    | Python     |
| Charlie | DevOps     | Go         |
```

**It renders as:**

> | Name    | Role       | Language   |
> |---------|------------|------------|
> | Alice   | Frontend   | TypeScript |
> | Bob     | Backend    | Python     |
> | Charlie | DevOps     | Go         |

**Alignment — you write:**

```markdown
| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Left         |    Center      |         Right |
```

**It renders as:**

> | Left-aligned | Center-aligned | Right-aligned |
> |:-------------|:--------------:|--------------:|
> | Left         |Center      |         Right |

- `:---` = left align
- `:---:` = center align
- `---:` = right align

---

### Horizontal Rule

**You write:**

```markdown
Some text above

---

Some text below
```

**It renders as:**

> Some text above
>
> ---
>
> Some text below

---

### Task Lists (Checkboxes)

**You write:**

```markdown
- [x] Create GitHub account
- [x] Create special repo
- [ ] Write awesome README
- [ ] Share with the world
```

**It renders as:**

> - [x] Create GitHub account
> - [x] Create special repo
> - [ ] Write awesome README
> - [ ] Share with the world

---

### Collapsible Sections

**You write:**

```markdown
<details>
<summary>Click to expand</summary>

Hidden content goes here.
You can put **markdown** inside too.

</details>
```

**It renders as:**

> <details>
> <summary>Click to expand</summary>
>
> Hidden content goes here.
> You can put **markdown** inside too.
>
> </details>

---

### Emoji

**You write:**

```markdown
:fire: :rocket: :star: :wave: :computer: :heart:
```

**It renders as:**

> :fire: :rocket: :star: :wave: :computer: :heart:

Full list: [emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet)

---

### Centering Content

GitHub Markdown supports some HTML.

**You write:**

```markdown
<div align="center">
  <h2>I'm centered!</h2>
  <p>This paragraph is also centered.</p>
</div>
```

**It renders as:**

> <div align="center">
>   <h2>I'm centered!</h2>
>   <p>This paragraph is also centered.</p>
> </div>

---

### Quick Reference Cheat Sheet

| You Write | It Renders As |
|-----------|---------------|
| `# Big Heading` | <h1>Big Heading</h1> |
| `## Smaller Heading` | <h2>Smaller Heading</h2> |
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `***bold italic***` | ***bold italic*** |
| `~~strikethrough~~` | ~~strikethrough~~ |
| `` `inline code` `` | `inline code` |
| `[text](url)` | [text](https://example.com) |
| `![alt](image-url)` | *(displays an image)* |
| `- item` | • item (bullet point) |
| `1. item` | 1. item (numbered) |
| `> quote` | (indented blockquote) |
| `---` | *(horizontal line)* |
| `- [x] done` | ☑ done (checked box) |
| `- [ ] todo` | ☐ todo (unchecked box) |


