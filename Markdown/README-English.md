# Github Markdown

## 1. Header

- Can be used with `#`.
- The more `#` symbols used, the smaller the font size becomes.

### Result:

# h1

## h2

### h3

#### h4

##### h5

###### h6

## 2. Emphasis

- `* text * or _ text _` will italicize the text.
- `** text ** or __ text __` will bold the text.
- `~~ text ~~` will add a strikethrough to the text.

### Result:

- _Italic text_
- **Bold text**
- ~~Strikethrough~~

## 3. Blockquotes

- Use `>` to create blockquotes.
- Up to 3 `>` can be used (nested quotes).
- You can use `> [!Note]` to highlight important information within the document.

### Result:

> Blockquote
>
> > Nested blockquote
> >
> > > Nested blockquote within a nested blockquote

> [!NOTE]
> Provides additional context that users should consider.  
> While users can proceed without the information in the note, it may be helpful for some users in certain contexts.

> [!TIP]
> Recommendations, best practices, or product hints.  
> Tips contain non-essential information that users can choose to follow, especially useful in documents aimed at new users.

> [!WARNING]
> Highlights potential risks that users should be aware of before starting or continuing a task.  
> Warning alerts are particularly relevant to processes occurring outside the GitHub UI, such as through the command line or API.

> [!CAUTION]
> Warns users about risky or destructive actions that require extreme caution before proceeding, especially in cases of security risks or potential data loss.  
> Caution alerts are generally only necessary when describing processes occurring outside the GitHub UI, such as through the command line or API.

## 4. List

### 4.1: Unordered List

---

- Can be created using `*`, `+`, or `-`.
- Indentation changes the appearance.

### 4.2: Ordered List

---

- Can be created using numbers (1, 2, 3...).
- Indentation changes the appearance.

### Result:

- Item 1
  - Item 2
    - Item 3

1. Item 1
2. Item 2
3. Item 3
   1. Item 1
   2. Item 2
   3. Item 3
      1. Item 1
      2. Item 2
      3. Item 3

## 5. Code

````
```(Language)

- Code goes here -

```
````

### Result:

```html
<p>Hello world!</p>
```

```js
console.log("Hello world!");
```

_Etc.._

## 6. Task List

- Use `- []` to indicate an incomplete list.
- Conversely, `- [x]` indicates a completed list.

### Result:

- [ ] Decorate README
- [x] Create README

## 7. Table

- Can be created using `|`, and
- To separate headers and cells, use `-`.

```
Header1|Header2|Header3|Header4
---|---|---|---
Cell1|Cell2|Cell3|Cell4
Cell5|Cell6|Cell7|Cell8
Cell9|Cell10|Cell11|Cell12
```

### Result:

| Header1 | Header2 | Header3 | Header4 |
| ------- | ------- | ------- | ------- |
| Cell1   | Cell2   | Cell3   | Cell4   |
| Cell5   | Cell6   | Cell7   | Cell8   |
| Cell9   | Cell10  | Cell11  | Cell12  |

## 8. Link

```
Inline link: [link](http://example.com "link title")
URL link: <example.com>, <example@example.com>; links are automatically created without angle brackets
```

### Result:

[Google](http://www.google.com "Google")  
[Naver](http://www.naver.com "Naver")  
[Github](http://www.github.com "Github")

## 9. Img

- To use an image, you can use `![alt](image_URL)`.

### Result:

![octocat](https://github.com/user-attachments/assets/f4d80d5e-a241-4aae-bccb-b544e7c487e6)
