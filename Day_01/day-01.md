
---

### **Your Quick Revision Notes for Today(HTML Cheat Sheet)**

*(Bookmark this to skim in 2 minutes tomorrow)*

**1. How the Web Works:**

* **Client (browser)** asks → **Server** serves → sometimes talks to **Database**.
* They talk using **HTTP** (the “language” of web requests).

**2. Boilerplate HTML Structure:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <!-- Visible content goes here -->
  </body>
</html>
```

Here are the **most useful tags** you’ll use often (don’t try to memorize them all at once — just keep this for reference):

#### **Structure**

```html
<!DOCTYPE html>   <!-- Tells the browser it's an HTML5 page -->
<html>            <!-- Wraps the entire page -->
<head>            <!-- Info about the page (title, links, meta info) -->
  <title>Page Title</title>
</head>
<body>            <!-- The visible content of the page -->
</body>
</html>
```

#### **Text**

```html
<h1>Heading 1</h1>   <!-- Biggest heading -->
<h2>Heading 2</h2>   <!-- Smaller heading -->
<p>Paragraph text goes here.</p>  
<b>Bold text</b>  
<i>Italic text</i>  
```

#### **Links & Images**

```html
<a href="https://example.com">Click me!</a>    <!-- Link -->
<img src="image.jpg" alt="Description">       <!-- Image -->
```

#### **Lists**

```html
<ul>                      <!-- Unordered (bullet) list -->
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ol>                      <!-- Ordered (numbered) list -->
  <li>First</li>
  <li>Second</li>
</ol>
```

#### **Tables & Forms**

```html
<table>
  <tr><th>Name</th><th>Age</th></tr>
  <tr><td>Alice</td><td>25</td></tr>
</table>

<form>
  <input type="text" placeholder="Your Name">
  <button>Submit</button>
</form>
```

*(Keep this cheat sheet handy — you’ll use these 90% of the time.)*

---

**3. Common Tags:**

* **Headings:** `<h1>` to `<h6>` (biggest → smallest).
* **Paragraph:** `<p>`.
* **Links:** `<a href="URL">Click Me</a>`.
* **Images:** `<img src="image.jpg" alt="desc">`.
* **Lists:**

  * Unordered: `<ul><li>Item</li></ul>`
  * Ordered: `<ol><li>Item</li></ol>`
* **Tables:**

  * `<table>` = whole table.
  * `<tr>` = row.
  * `<th>` = header cell.
  * `<td>` = data cell.

*(Keep today’s **HTML cheat sheet** handy for reference.)*

---