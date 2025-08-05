
## **Lists**

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
## Tables
* Tables are used to represent real life table data.
  * `<table>` = whole table.
  * `<tr>` = row.
  * `<th>` = header cell.
  * `<td>` = data cell.

* **Caption in Tables**
  * `<caption> Student Data </caption>`

* **thead & tbody in Tables**
  * `<thead>` to wrap table head
  * `<tbody>` to wrap table body

* **colspan attribute**
  * `<th colspan="n">`
  * used to create cells which spans over multiple columns

## Forms

Forms let users **enter data** (like login, search, or feedback).

Basic structure:

```html
<form action="/submit" method="post">
  <input type="text" name="username" placeholder="Enter your name">
  <button type="submit">Send</button>
</form>
```

* `<form>` wraps all input fields.
* `action` = where the data is sent.
* `method` = how it’s sent (`get` or `post`).
* `<input>` creates fields (text, password, email, etc.).
* `<button>` or `<input type="submit">` submits the form.

* **Lable**
```html
<p>Select your gender:</p>
  <input type="radio" id="male" name="gender" value="male"> <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female"> <label for="female">Female</label>
  <input type="radio" id="other" name="gender" value="other"> <label for="other">Other</label>
```

* **Class & Id**
  * `<div id="id1" class="group1"> </div>`
  * `<div id="id2" class="group1"> </div>`

* **Checkbox**
```html
<input type="checkbox" value="class X" name="class" id="id1"> <label for="id1"></label>

<input type="checkbox" value="class X" name="class" id="id2"> <label for="id2"></label>
```
* **Textarea**
```html
<textarea name="feedback" id="feedback" placeholder="Please add Feedback"> </textarea>
```
* **Select**
```html
<select name="city" id="city">
  <option value="Delhi"> Delhi </option>
  <option value="Mumbai"> Delhi </option>
  <option value="Banglore"> Delhi </option>
</select>
```
## iframe Tag
* website inside website `<iframe src="link"> Link </option>`

## Video Tag
```html
<video src="myVid.mp4"> My Video </video>
```
***<u>Attributes</u>***
- controls
- height
- width
- loop
- autoplay

---
