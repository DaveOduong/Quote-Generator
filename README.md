# RANDOM QUOTE GENERATOR

## 1. Project Description
Random Quote Generator is a simple web application built using HTML and JavaScript. It displays randomly selected Bible verses whenever the user clicks the Generate Quote button.

## 2. Features
- Generates random Bible verses from a collection of quotes.
- Prevents repeating a quote until all quotes have been displayed.
- Automatically resets the selection after all quotes have been used.
- Displays the selected quote directly on the webpage.

## 3. Technologies Used
- **HTML:** Creates the webpage structure, quote display area, and button.
- **JavaScript:** Handles random selection, duplicate prevention, and quote display.

## 4. Project Files
- `index.html` – Contains the webpage structure and button.
- `script.js` – Contains the Bible verses and JavaScript functions.

## 5. How to Run
1. Save the HTML code as `index.html`.
2. Save the JavaScript code as `script.js`.
3. Place both files in the same folder.
4. Open `index.html` in a web browser.
5. Click **Generate Quote** to display a random Bible verse.

## 6. JavaScript Concepts Used

**Array**

Stores the collection of Bible verses.

**Set**

Stores indexes of previously displayed quotes to prevent repetition.

**Math.random()**

Generates a random number used to select a quote.

**Math.floor()**

Rounds the random number down to produce a valid array index.

**generateQuote()**

Selects and displays a random quote while ensuring that previously displayed quotes are not repeated until the collection is exhausted.

**clear()**

Resets the Set when all available quotes have been displayed.

## 7. Conclusion
This project demonstrates JavaScript arrays, Sets, random number generation, loops, conditional statements, DOM manipulation, and duplicate prevention in a simple interactive application.
