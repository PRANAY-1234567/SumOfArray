# ➕ Sum of Array Elements in JavaScript

A simple JavaScript program that calculates the **sum of all elements in an array** using the built-in `reduce()` method.

This project demonstrates how JavaScript array methods can be used to process and calculate values efficiently.

---

## 📌 Overview

The program defines a reusable `sumArray()` function that accepts an array of numbers and returns the total sum of all its elements.

For example:

```text
[1, 2, 3, 4]
```

The calculated result is:

```text
10
```

---

## 🚀 Features

* Calculates the sum of array elements
* Uses JavaScript's `reduce()` method
* Reusable function implementation
* Simple and beginner-friendly
* Works with arrays containing numeric values

---

## 🛠️ Technologies Used

* **JavaScript (ES6+)**
* Array `reduce()` method

---

## 📂 Project Structure

```text
JavaScript-Array-Sum/
│
├── sumArray.js
└── README.md
```

---

## 💻 Source Code

```javascript
function sumArray(arr) {
  return arr.reduce((sum, val) => sum + val, 0);
}

console.log(sumArray([1, 2, 3, 4]));
```

---

## ▶️ How to Run

### Using Node.js

Make sure Node.js is installed, then run:

```bash
node sumArray.js
```

### Using a Browser

You can also run the program through the browser's Developer Console:

1. Open a browser.
2. Press `F12`.
3. Open the **Console** tab.
4. Paste the JavaScript code.
5. Press **Enter**.

---

## 📋 Sample Output

```text
10
```

---

## 🧠 How It Works

The `sumArray()` function uses the JavaScript `reduce()` method:

```javascript
arr.reduce((sum, val) => sum + val, 0);
```

The `reduce()` method processes each element of the array and maintains a running total.

For the array:

```text
[1, 2, 3, 4]
```

The calculation happens as:

```text
0 + 1 = 1
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10
```

Final result:

```text
10
```

---

## 📖 Algorithm

1. Start the program.
2. Create an array containing numbers.
3. Pass the array to the `sumArray()` function.
4. Use `reduce()` to iterate through each element.
5. Add each element to the running sum.
6. Return the final sum.
7. Display the result using `console.log()`.

---

## ⏱️ Complexity Analysis

| Metric           | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(n)**   |
| Space Complexity | **O(1)**   |

Where `n` is the number of elements in the array.

---

## 🎯 Concepts Covered

* JavaScript Functions
* Arrays
* `reduce()` Method
* Arrow Functions
* Callback Functions
* Return Values
* Console Output

---

## 🔮 Future Improvements

* Accept array input from the user
* Calculate average of array elements
* Find minimum and maximum values
* Calculate sum of only even numbers
* Calculate sum of only positive numbers
* Create a web-based array calculator

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | Java | JavaScript | SQL | Data Analytics

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and contribute for educational and learning purposes.

---

⭐ If you found this project helpful, don't forget to **Star** the repository!


<img width="817" height="615" alt="image" src="https://github.com/user-attachments/assets/fc6c4daa-3975-4358-a2cb-003eec471ead" />
