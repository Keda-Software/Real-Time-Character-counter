# Real-Time-Character-counter

# 🔢 Real-Time Character Counter

## 📌 Project Description

The **Real-Time Character Counter** is a simple and interactive web application built using HTML, CSS, and JavaScript. It allows users to type text into a text area and instantly see the total number of characters entered and the number of characters remaining.

The application has a maximum character limit of **120 characters**, making it useful for practicing JavaScript DOM manipulation and event handling.

## ✨ Features

- 🔄 Real-time character counting
- 🔢 Displays the total number of characters typed
- 📉 Shows the number of remaining characters
- 🚫 Limits input to 120 characters
- 🎨 Simple and colorful user interface
- 📱 Basic responsive layout
- ⚡ Instant updates while typing

## 🛠️ Technologies Used

- **HTML5** – Structures the web page.
- **CSS3** – Styles the application and creates the layout.
- **JavaScript** – Implements the character-counting functionality.

## 📂 Project Structure

```text
Real-Time-Character-Counter/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder in Visual Studio Code.

3. Make sure `index.html`, `style.css`, and `script.js` are in the correct locations.

4. Open `index.html` in your browser, or use the Live Server extension in VS Code.

5. Start typing in the text area to see the character counter update.

## 🧠 What I Learned

Through this project, I practiced:

- Selecting HTML elements using `getElementById()` and `querySelector()`.
- Handling keyboard events using `addEventListener()`.
- Reading user input using the `value` property.
- Counting characters using the JavaScript `length` property.
- Updating HTML content dynamically using `innerText`.
- Applying the HTML `maxlength` attribute.
- Linking external CSS and JavaScript files to an HTML document.

## 💻 How It Works

1. The user enters text into the text area.
2. JavaScript detects the typing event.
3. The application calculates the total number of characters.
4. The remaining character count is calculated by subtracting the entered characters from 120.
5. Both counters update automatically.

**Formula:**

```javascript
Total Characters = textarea.value.length;

Remaining Characters = 120 - textarea.value.length;
```

## 🎯 Project Goal

The goal of this project is to strengthen my foundational knowledge of HTML, CSS, and JavaScript by building a practical application with real-time user interaction.

## 👨‍💻 Author

**Keda Software**

GitHub: [Visit My GitHub Profile](https://github.com/Keda-Software)

-
