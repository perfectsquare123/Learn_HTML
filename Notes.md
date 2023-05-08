# The Complete 2023 Web Development Bootcamp

## Section 2: Introduction to HTML

### 1. Headings Elements

- hierachy
- NO `<h7></h7>`
- NO more than one `<h1></h1>`
- DON'T skip hierachy level
- more info: <link href = "https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link">headings</link>

```html
<h1>Hello World</h1>
```

| `<h1>`      | Hello World | `</h1>`   |
| ----------- | ----------- | --------- |
| opening tag |             | close tag |
|             | element     |           |

### 2. Paragraph Elements

- know where is being seperated
- seperated by a line

```html
<p>This is a paragraph.</p>
```

### 3. Void Elements

- The above 2 are non void
- can also be written as `<hr>`, `<br>`

  #### a. Horizontal Rule Element

  - form a horizontal break out line

    ```html
    <hr />
    ```

  #### b. Break Element

  - show the break in paragraphs (like ENTER)

  ```html
  <p>
    This is a paragraph. <br />
    This is a paragraph.
  </p>
  ```

## Section 3: Intermediate HTML

### 1. List Element

#### a. unordered list

- result in bullet form

```html
<ul>
  <li>flour</li>
  <li>code</li>
  <li>some</li>
</ul>
```

_Result: _

  <ul>
    <li>flour</li>
    <li>code</li>
    <li>some</li>
  </ul>

#### b. ordered list

- result in numbers bullet

```html
<ol>
  <li>flour</li>
  <li>code</li>
  <li>some</li>
</ol>
```

**Result:**

  <ol>
    <li>flour</li>
    <li>code</li>
    <li>some</li>
  </ol>

#### c. nested list

- use indentation to make nested

```html
<ul>
  <li>
    A
    <ol>
      <li>A1</li>
      <li>A2</li>
    </ol>
  </li>
  <li>B</li>
</ul>
```

**Result:**

<ul>
  <li>A
    <ol>
      <li>A1</li>
      <li>A2</li>
    </ol>
  </li>
  <li>B</li>
</ul>

### 2. Anchor Element

Format:

> ```html
> <tag attribute="value" anotherattribute="value">Content</tag>
> ```

Resource:

<link href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol">list</link>
