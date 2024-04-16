# DOM Styling with JavaScript README

This project demonstrates how to manipulate DOM (Document Object Model) properties using JavaScript to dynamically change the style of a `<div>` element. The example covers setting properties such as margin, padding, and color using JavaScript.

## Getting Started

To run and test this project locally, follow these instructions:

### Prerequisites

- A modern web browser that supports JavaScript

### Installation

1. Clone or download this repository to your local machine.

```bash
git clone https://github.com/your-username/dom-styling.git
```

2. Navigate to the project directory.

```bash
cd dom-styling
```

### Usage

1. Open `index.html` in your web browser.
2. You should see a styled `<div>` element rendered on the page.
3. Open `script.js` to view and modify the JavaScript code responsible for styling the `<div>`.

### DOM Styling Techniques

The `script.js` file demonstrates how to use JavaScript to style a `<div>` element by manipulating its DOM properties. Here are the techniques used:

- **Changing Margin:**

  ```javascript
  const myDiv = document.getElementById("myDiv");
  myDiv.style.margin = "20px";
  ```

- **Changing Padding:**

  ```javascript
  const myDiv = document.getElementById("myDiv");
  myDiv.style.padding = "10px";
  ```

- **Changing Text Color:**

  ```javascript
  const myDiv = document.getElementById("myDiv");
  myDiv.style.color = "blue";
  ```

Feel free to modify the values and experiment with other CSS properties!

## Acknowledgments

- This project is for learning purposes and demonstrates basic DOM manipulation techniques.
- Inspired by Geekster.

---

In this README template:

- **Overview:** Provides a brief introduction to the project and its purpose.
- **Getting Started:** Instructions on how to set up and run the project locally.
- **Usage:** Steps to view and interact with the project.
- **DOM Styling Techniques:** Describes the JavaScript techniques used to manipulate DOM properties for styling.
- **Acknowledgments:** Credits and references.
