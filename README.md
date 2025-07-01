# 🧭 Pathfinding Visualizer

A visual and interactive tool to demonstrate popular pathfinding algorithms like Dijkstra's, A*, BFS, and DFS. Built with **React**, this project helps you understand how algorithms find the shortest path on a grid.


## 🚀 Features

- Interactive grid where users can set start, end, and wall nodes
- Visual animations for:
  - Dijkstra’s Algorithm
  - A* Search
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
- Adjustable grid size and speed controls (if added)
- Clean UI with real-time animation of visited and shortest paths

---

## 🛠️ Tech Stack

- **Frontend:** React.js (Create React App)
- **Styling:** CSS
- **Bundler:** Webpack (via `react-scripts`)

---

## 🖥️ Getting Started

### ✅ Prerequisites

- Node.js (Recommended: **v16**)
- npm (comes with Node.js)

> 💡 _If you're using Node.js v17 or higher, see the note below on OpenSSL issues._

---

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pathfinding-visualizer.git
   cd pathfinding-visualizer

    npm install
    set NODE_OPTIONS=--openssl-legacy-provider
    npm start


