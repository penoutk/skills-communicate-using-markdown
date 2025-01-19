# Communicate using Markdown

<img src=https://commonmark.org/help/images/favicon.png alt=markdown width=250 align=right>

**What is Markdown?** <ins>***Markdown***</ins> is a simple way to format text that looks great on any device. It doesn’t do anything fancy like change the font size, color, or type — just the essentials, using keyboard symbols you already know. You can format text to add a heading, lists, bold, italics, tables, and many other stylings. You can use Markdown in most places around GitHub:

- Comments on issues, pull requests, and discussions
- Files with the .md or .markdown extension
- Sharing snippets of text in Gists

### Headings

**What is a header?** A <ins>***header***</ins> is a larger bit of text at the beginning of a section. There are six sizes.

#### Example

> ```markdown
> # Heading 1
> ## Heading 2
> ##### Heading 4
> ```

### Images

<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>

Images are almost identical to links, but an image starts with an exclamation point `!`. Include descriptive text in the square brackets `![alt-text](image.png)`. This alternate (alt) text is displayed when the image can't be shown, or for the visually impaired. It's also shown at times when your image doesn't display, such as when there's a poor connection. Additionally this text is read aloud for people using screen readers.

### Code Blocks

To create inline code, wrap with backticks `` ` `` and to create a code block, sometimes called a “code fence”, either indent each line by 4 spaces, or place 3 backticks ` ``` ` on a single line above and below the code block. One level of indentation in a code block equals 4 spaces or one tab. An indented code block continues until it reaches a line that is not indented. A code block or span displays every character inside *exactly* as it was typed. However, code blocks can render differently depending on the language.

#### Example

> ```javascript
> let greeting = "Hello, world!";
>
> console.log(greeting);
> ```

### Task Lists

**What is a task list?** A <ins>***task list***</ins> creates checkboxes to check off. They're very useful for tracking issues and pull requests. If you include a task list in the body of an issue or pull request, you'll see a progress indicator in your issue list. The syntax for task lists is very specific. Be sure to include the spaces where required, or else they won't render.

#### Example

> ```markdown
> - [x] Turn on GitHub Pages
> - [ ] Outline my portfolio
> - [ ] Introduce myself to the world
> ```

Remember, a task list starts with the syntax `- [ ]`, followed by a space ` ` and then the task list item. The formatting is specific!
