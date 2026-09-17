# ADSA Interactive Learning Lab

A highly interactive Advanced Data Structures & Algorithms learning platform.

ADSA Interactive Learning Lab is a hands-on educational platform engineered to make complex algorithmic concepts, tree balancing, graph traversals, hashing mechanisms, string matching, and dynamic programming immediately intuitive through visual, step-by-step interactive simulations.

---

## Overview

The platform allows students, educators, and engineers to understand algorithms and data structures through:
- **Interactive Visualizations**: Real-time manipulation of trees, heaps, graphs, hash tables, and string matching automata.
- **Step-by-Step Execution**: Play, pause, step forward/backward, and adjust execution speed to observe invariant states.
- **Algorithm Simulations**: Dynamic side-by-side race comparisons and live benchmarks across sorting, pathfinding, and searching.
- **Complexity Analysis**: Deep dives into time and space complexities (best, average, worst cases) with mathematical explanations.
- **Interactive Learning Experiences**: Guided curriculum covering 6 core units from basic dictionaries to advanced algorithm design paradigms.

---

## Major Features

1. **Balanced Trees & Heaps**
   - Binary Search Trees (BST), AVL Trees (with automatic rotation animations), Red-Black Trees, 2-3 Trees / B-Trees, Splay Trees, and Min/Max Heaps.
2. **Advanced Hashing Laboratory**
   - Hash function visualizer, collision resolution techniques (Separate Chaining, Linear Probing, Quadratic Probing, Double Hashing), Rehashing, and Extendible Hashing.
3. **Graph Algorithms**
   - Breadth-First Search (BFS), Depth-First Search (DFS), Dijkstra's Shortest Path, Bellman-Ford, and Topological Sorting with customizable graph topologies.
4. **Text Processing & Compression**
   - Brute Force String Matching, Knuth-Morris-Pratt (KMP) failure functions, Boyer-Moore, Standard & Suffix Tries, Huffman Coding Tree & bitstream generation, and Longest Common Subsequence (LCS).
5. **Algorithm Design Techniques**
   - Interactive sandboxes for Divide & Conquer, Greedy approaches, Dynamic Programming (memoization & tabulation tables), Backtracking (N-Queens), and Branch & Bound.
6. **Algorithm Race Sandbox**
   - Direct execution head-to-head racing comparing algorithmic operations, iteration counts, and runtime performance.
7. **Neo-Brutalist Technical Interface**
   - High-contrast visual design, tactile controls, dual-theme support (Dark & Light modes), responsive layouts, and synchronized code view.

---

## Technologies Used

- **Framework**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Bundler & Tooling**: [Vite](https://vitejs.dev/)
- **Animations & Motion**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Code Syntax Highlighting**: [React Syntax Highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter)
- **Routing**: [React Router v7](https://reactrouter.com/)
- **Styling**: Vanilla CSS tokens & Neo-Brutalist design architecture

---

## Getting Started Locally

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18+ recommended)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yuvrajkale95/ADSA-Interactive-Learning-Lab.git
   cd ADSA-Interactive-Learning-Lab
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running Locally

Start the local development server:
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### Building for Production

To create an optimized production build:
```bash
npm run build
```
The compiled output will be generated in the `dist/` directory.

To preview the production build locally:
```bash
npm run preview
```

---

## License

MIT
