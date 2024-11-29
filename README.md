## Wavefunction Graph Plotter

### Overview

This project is a web-based application that allows users to plot wavefunctions using mathematical expressions. It utilizes Plotly for graphing and Math.js for mathematical evaluations, providing a user-friendly interface for visualizing complex functions.

### Features

- **Wavefunction Input**: Users can input any mathematical expression involving the variable x (e.g., `sin(x)`, `cos(x)`, `x^2`, etc.).
- **Graph Plotting**: The application generates a graph of the wavefunction over the range of x from -10 to 10.
- **Error Handling**: If there is an error in the wavefunction input, an alert will notify the user.

### Technologies Used

- **HTML/CSS**: For structuring and styling the web page.
- **JavaScript**: For dynamic functionality, including plotting graphs and handling user input.
- **Plotly.js**: A JavaScript library for creating interactive graphs.
- **Math.js**: A powerful library for mathematical computations.

### Installation

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.

### Usage

1. Open the application in your web browser.
2. Enter a wavefunction in the input field (e.g., `sin(x)`, `x^2`, `exp(-x^2)`).
3. Click the "Plot" button to generate the graph.
4. The graph will be displayed below the input form.

### Code Explanation

- **HTML Structure**: The HTML provides a simple layout with an input form and a div for displaying the graph.
  
- **CSS Styling**: The CSS styles enhance the appearance of the application, making it visually appealing and user-friendly.

- **JavaScript Functions**:
  - `appendToInput(value)`: Appends a value to the current input string.
  - `clearInput()`: Clears the current input string.
  - `plotGraph(event)`: Handles form submission, evaluates the wavefunction, and plots the graph using Plotly.

### Example Wavefunctions

Here are some example wavefunctions you can try:

- `sin(x)`
- `cos(x)`
- `tan(x)`
- `exp(-x^2)`
- `x^3 - 3*x + 2`

### Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements or new features.



For any questions or issues, please me contact [here](https://github.com/Lakshit2604).