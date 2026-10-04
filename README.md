# I-Frame Assignment Web Page

## 📌 Project Overview

This project is a simple **HTML and CSS based I-Frame Assignment Web Page**. It contains multiple assignment links on the left side and displays the selected assignment inside an **iframe** on the right side.

The project uses **Flexbox** to create a two-column layout.

---

## ✨ Features

* 📂 10 assignment links
* 🖥️ Two-column layout
* 🎨 Simple CSS styling
* 🔵 Blue rounded buttons
* 🖼️ Assignments displayed using an `<iframe>`
* 🔗 Links open inside the iframe
* 📱 Viewport meta tag for better device compatibility

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Flexbox**
* **I-Frame**

---

## 📁 Project Structure

```text
Project/
│
├── index.html
│
└── all/
    ├── Assignment-1.html
    ├── Assignment-2.html
    ├── Assignment-3.html
    ├── Assignment-4.html
    ├── Assignment-5.html
    ├── Assignment-6/
    │   └── 1index.html
    ├── Assignment-7.html
    ├── Assignment-8.html
    ├── Assignment-9.html
    ├── Assignment-10.html
    └── 1.png
```

---

## 🖼️ I-Frame Layout

The webpage is divided into two sections:

### Left Section

The left section contains buttons for all 10 assignments.

Each button contains a link to an assignment page.

### Right Section

The right section contains an **I-Frame** where the selected assignment page is displayed.

The right section occupies **70%** of the page width.

---

## 💻 I-Frame Used in the Project

```html
<iframe 
    src="all/1.png"
    frameborder="0"
    height="100%"
    width="100%"
    name="vikash">
</iframe>
```

The `name="vikash"` attribute is used as the target for the assignment links.

---

## 🔗 Target Attribute

Each assignment link uses:

```html
target="vikash"
```

For example:

```html
<a href="all/Assignment-1.html" target="vikash">
    Assignment-1
</a>
```

The `target` value matches the iframe's `name`:

```html
name="vikash"
```

Therefore, when an assignment link is clicked, the page opens inside the I-Frame.

---

## 🎨 CSS Concepts Used

### Flexbox

```css
.box {
    display: flex;
}
```

Flexbox is used to create the left and right sections.

### Column Layout

```css
.left {
    display: flex;
    flex-direction: column;
}
```

This places all assignment buttons vertically.

### Space Evenly

```css
justify-content: space-evenly;
```

This distributes the buttons evenly inside the left section.

### Rounded Buttons

```css
border-radius: 30px;
```

This gives the assignment buttons rounded corners.

---

## 🚀 How to Run

1. Download or clone the project.
2. Keep the `all` folder in the same location as `index.html`.
3. Make sure all assignment files are present.
4. Open `index.html` in a browser.
5. Click any assignment button.
6. The selected assignment will open inside the **I-Frame**.

---

## 📚 Learning Outcomes

Through this project, you can learn:

* HTML5 structure
* CSS styling
* Flexbox
* I-Frame
* Hyperlinks
* `target` attribute
* Relative file paths
* Displaying one HTML page inside another page

---

## 👨‍💻 Author

**Vikash Kumawat**

---

## 📄 License

This project is created for **educational and assignment purposes**.
