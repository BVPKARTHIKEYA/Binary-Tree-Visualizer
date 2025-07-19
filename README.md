# 🌳 Binary Tree Visualization

An interactive web application that helps users understand how arrays are transformed into various tree structures like **Binary Trees**, **Max-Heaps**, and **Binary Search Trees (BSTs)**. Built using **HTML**, **Tailwind CSS**, and **D3.js**, this visualizer is a helpful educational tool for students, educators, and anyone learning about data structures.

---

## 📌 Features

- ✅ **Input any array** to see how it is structured in different types of trees.
- 🌿 **Binary Tree Visualization** – Converts the array into a generic binary tree format.
- 🔺 **Max-Heap Visualization** – Demonstrates heapification based on max-heap rules.
- 🔍 **Binary Search Tree (BST) Visualization** – Inserts values in BST order.
- 🎨 Built with **Tailwind CSS** for responsive UI.
- 📈 Uses **D3.js** to render interactive, scalable tree diagrams.

---

## 🧠 How It Works

1. Enter a comma-separated array (e.g., `10, 5, 20, 3, 7`).
2. Click one of the buttons:
   - **Binary Tree** – Shows a level-order tree from the array.
   - **Max-Heap** – Visualizes the max-heap formed by heapifying the array.
   - **BST** – Inserts elements into a binary search tree in the order given.
3. The tree is drawn dynamically using D3.js below the controls.

---

## 📂 File Structure

├── index.html # Main HTML page
├── app.js # Binary tree and BST visualization logic
├── heap.js # Heap visualization logic
├── nodes.js # Utility for creating and positioning tree nodes
|__ styles.css # For Styling


---

## 🛠 Technologies Used

- [Tailwind CSS](https://tailwindcss.com/) – Styling
- [D3.js](https://d3js.org/) – Tree drawing and manipulation
- JavaScript – Logic for tree operations

---
