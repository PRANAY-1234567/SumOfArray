➕ Sum of Array Elements in JavaScript

📌 Description

This JavaScript program calculates the sum of all elements in an array using the built-in reduce() method.

✅ Code

function sumArray(arr) {
  return arr.reduce((sum, val) => sum + val, 0);
}

console.log(sumArray([1, 2, 3, 4]));

🧠 How It Works

🔹 reduce() Method

reduce() is used to combine all array values into a single value.

Syntax:
array.reduce((accumulator, currentValue) => {}, initialValue);

In this program:

sum → accumulator (stores running total)

val → current array element
0 → starting value of sum
So it works like:
0 + 1 = 1
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10

🖨 Example Output
10

🛠 Concepts Used

Functions in JavaScript
Arrays
Arrow Functions (=>)
reduce() method

🎯 Use Cases

Data processing
Finding totals (marks, prices, etc.)
Interview coding questions
Learning functional programming

🚀 Possible Improvements

Handle empty arrays
Accept user input
Find average using sum
Sum only even/odd numbers

👨‍💻 Author
Pranay Jadhao

<img width="817" height="615" alt="image" src="https://github.com/user-attachments/assets/fc6c4daa-3975-4358-a2cb-003eec471ead" />
