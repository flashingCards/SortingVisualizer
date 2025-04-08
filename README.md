# Sorting Visualizer 🧮✨

An interactive and animated sorting algorithm visualizer built with **Next.js** and deployed on **Vercel**. This project brings sorting algorithms to life through sleek, real-time animations, making it easier to understand how they work under the hood.

![Sorting Visualizer Screenshot](./Screenshot%202025-04-08%20232339.png)

---

## 🔗 Live Demo

🚀 [Check it out on Vercel](https://sorting-visualizer-next-8q2wlpypl-divash-krishnams-projects.vercel.app/)  


---

## ✨ Features

- 🔀 Random array generation
- 🎞️ Smooth visual animations for all sorting steps
- 🕹️ Speed control (Slow → Fast)
- 📚 Algorithm selection from dropdown
- 📈 Time complexity details for each algorithm

---

## 📚 Sorting Algorithms

### 🫧 Bubble Sort
- Repeatedly swaps adjacent elements if they are in the wrong order.
- **Worst Case:** `O(n²)`  
- **Average Case:** `O(n²)`  
- **Best Case:** `O(n)`

---

### ⚡ Quick Sort
- Selects a pivot and partitions the array into two halves, recursively sorting each part.
- **Worst Case:** `O(n²)`  
- **Average Case:** `O(n log n)`  
- **Best Case:** `O(n log n)`

---

### 🧬 Merge Sort
- Divides the array into halves, sorts and merges them recursively.
- **Worst Case:** `O(n log n)`  
- **Average Case:** `O(n log n)`  
- **Best Case:** `O(n log n)`

---

### 🧷 Insertion Sort
- Builds the final sorted array one item at a time.
- **Worst Case:** `O(n²)`  
- **Average Case:** `O(n²)`  
- **Best Case:** `O(n)`

---

### 📌 Selection Sort
- Selects the smallest element and moves it to the correct position iteratively.
- **Worst Case:** `O(n²)`  
- **Average Case:** `O(n²)`  
- **Best Case:** `O(n²)`

---

## 🛠️ Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/yourusername/sorting-visualizer.git
cd sorting-visualizer
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

---

## 📁 Project Structure

```
sorting-visualizer/
├── components/
│   ├── SortingVisualizer.jsx
│   └── Controls.jsx
├── algorithms/
│   ├── bubbleSort.js
│   ├── quickSort.js
│   ├── mergeSort.js
│   ├── insertionSort.js
│   └── selectionSort.js
├── pages/
│   └── index.js
├── styles/
│   └── globals.css
├── public/
├── next.config.js
└── README.md
```

---

## 🧑‍🎨 Built With

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/) *(optional)*
- [Vercel](https://vercel.com/) for deployment

---

## 🚀 Deployment

This project is seamlessly deployed with **Vercel**. Just push to your GitHub repo and Vercel handles the rest!

---

## 💡 Future Improvements

- Add Heap Sort and Radix Sort
- Add sound effects for sorting actions
- Allow users to input custom arrays
- Dark/light theme toggle

---

