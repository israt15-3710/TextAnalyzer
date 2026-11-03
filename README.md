# Text Length Checker

## About the Project

Text Length Checker is a simple web application developed using HTML, CSS, and JavaScript. It allows users to enter text and check its character length and word count.

The application detects whether the entered text contains a single word or multiple words. For a single word, it displays the word's character length. For multiple words, it displays the total character length and word count.

This project is designed for beginners to practice JavaScript functions, conditional statements, loops, string manipulation, and DOM (Document Object Model) operations.

## Features

- Simple and user-friendly interface.
- Enter any text into the text box.
- Detects single-word and multiple-word input.
- Displays the character length of a single word.
- Displays total character length and word count for multiple words.
- Shows an alert when the text box is empty.
- Works directly in a web browser.
- No additional installation required.

## Technologies Used

- **HTML:** Creates the structure of the webpage.
- **CSS:** Provides styling and improves the user interface.
- **JavaScript:** Processes the input and displays the results.

## How It Works

1. The user enters text into the text box.
2. The user clicks the **Check** button.
3. JavaScript reads the entered text.
4. The `trim()` function removes leading and trailing spaces.
5. The program checks the input:
   - **Single Word:** Displays the character length of the word.
   - **Multiple Words:** Displays the total character length and word count.
   - **Empty Input:** Displays an alert asking the user to enter text.
6. The result appears below the button.

## Example Outputs

### Example 1: Single Word

**Input:**
```text
Hello
```

**Output:**
```text
Single word detected.
Length: 5 characters.
```

### Example 2: Multiple Words

**Input:**
```text
Hello World
```

**Output:**
```text
Full text detected (2 words).
Total length: 11 characters.
```

### Example 3: Multiple Words with Extra Spaces

**Input:**
```text
Hello World 
```

**Output:**
```text
Full text detected (2 words).
Total length: 12 characters.
```

### Example 4: Empty Input

**Input:**
```text
Nothing entered.
```

**Output:**
```text
Alert: Please enter some text before checking.
```

## JavaScript Concepts Used

- **Functions:** `checkText()` handles the text-checking operation when the button is clicked.
- **Variables:** Store the user's input and calculated results.
- **trim():** Removes spaces from the beginning and end of the text.
- **split():** Separates the text into individual words.
- **for loop:** Iterates through the words in an array.
- **if-else:** Handles single-word, multiple-word, and empty-input conditions.
- **length:** Calculates the number of characters and array elements.
- **innerHTML:** Displays the results on the webpage.
- **alert():** Shows a warning when the input is empty.

## Conclusion

Text Length Checker is a beginner-friendly JavaScript project that demonstrates basic text processing, functions, conditional statements, loops, and DOM manipulation.

It provides a practical way to understand how JavaScript interacts with HTML elements and processes user input in a web browser.


B.Sc. in Software Engineering

## License

This project is created for educational purposes.
