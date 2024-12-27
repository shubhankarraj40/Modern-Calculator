# Calculator

## <h2>Introduction</h2>
<p>This is a simple and modern calculator built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The design includes an animated bubble background for a sleek appearance.</p>

---

## <h2>Features</h2>
<ul>
  <li>Basic arithmetic operations: <code>+</code>, <code>-</code>, <code>*</code>, <code>/</code></li>
  <li>Responsive design for better usability</li>
  <li>Bubble animation in the background</li>
</ul>

---

## <h2>Logic of JavaScript</h2>
<p>The calculator's functionality is controlled by JavaScript, and here’s a breakdown of how it works:</p>

<ol>
  <li><strong>Display Updates:</strong> Every button press appends its corresponding value (number or operator) to the <code>currentDisplay</code> string. The <code>currentDisplay</code> string is shown in the calculator’s input field using the <code>value</code> property.</li>
  <li><strong>Clear Button:</strong> The "C" button resets the <code>currentDisplay</code> to an empty string, effectively clearing the calculator display.</li>
  <li><strong>Calculation Execution:</strong> When the <code>=</code> button is clicked, the <code>eval()</code> function evaluates the expression stored in <code>currentDisplay</code> and calculates the result. The result is then updated in the input field for the user to see.</li>
</ol>

---

## <h2>Key Keyword</h2>
<p>The <strong><code>eval()</code></strong> function is the core of the calculation logic. It takes a string input (e.g., <code>2+3*4</code>) and evaluates it as a mathematical expression. While it's simple and effective for basic calculators, it should be used cautiously in more complex applications due to potential security concerns.</p>

---

## <h2>How to Use</h2>
<ol>
  <li>Open the HTML file in a browser.</li>
  <li>Use the buttons to input numbers and operators.</li>
  <li>Press the <code>=</code> button to see the result.</li>
  <li>Use the "C" button to clear the display and start over.</li>
</ol>

---

## <h2>Future Improvements</h2>
<ul>
  <li>Add advanced features like percentage and square root.</li>
  <li>Improve security by replacing <code>eval()</code> with a custom parser.</li>
  <li>Support for keyboard input.</li>
</ul>

<p>Enjoy your sleek and modern calculator! 😊</p>


![Screenshot (325)](https://github.com/user-attachments/assets/138b6f57-259d-4f3e-bcea-3a2a7d536c1a)
