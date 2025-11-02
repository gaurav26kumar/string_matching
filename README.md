# 🔍 KMP String Matching Visualizer

This project demonstrates the *Knuth–Morris–Pratt (KMP)* algorithm for efficient string pattern searching.
It provides a simple, interactive web interface to input text and patterns, and visualize how KMP processes mismatches and pattern shifts step by step.

---

## 🚀 Features

* *Interactive Input:* Enter any text and pattern dynamically.
* *Step-by-Step Visualization:* Watch how KMP skips unnecessary comparisons.
* *Educational Focus:* Perfect for learning how string matching works under the hood.
* *Responsive UI:* Works smoothly in any modern web browser.

---

## 🧠 About the KMP Algorithm

The *Knuth–Morris–Pratt (KMP)* algorithm improves the efficiency of naive string matching by avoiding redundant comparisons.
It preprocesses the pattern to create an *LPS (Longest Prefix Suffix)* array that helps determine how far the pattern should shift upon a mismatch.

*Time Complexity:*

* Preprocessing: O(m)
* Searching: O(n)
  (where n = length of text, m = length of pattern)

---

## 💻 How to Run

1. Clone the repository:

   bash
   git clone https://github.com/gaurav26kumar/KMP_Algorithm_Visualizer.git
   cd KMP_Algorithm_Visualizer
   

2. Open the file:

   bash
   kmp_modified.html
   

3. Run in your browser — no installation needed.

---

## 🖼 Example

* Enter *Text:* ABABDABACDABABCABAB
* Enter *Pattern:* ABABCABAB
* Click on *Search* to visualize each step of the KMP process.

---

## 🧩 Technologies Used

* *HTML5* – for structure
* *CSS3* – for styling
* *JavaScript (ES6)* – for logic and interactivity



---

## 👨‍💻 Author

*Gaurav Kumar*
🟢 [GitHub Profile](https://github.com/gaurav26kumar)

> “Turning algorithms into visuals — one step at a time.”
