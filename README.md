# 🧠 Interactive Graph Builder with DFS Visualizer

An intuitive, interactive, and zoomable graph-building tool with depth-first search (DFS) visualization — built using [p5.js](https://p5js.org/).

## 🚀 Features

- ✅ Add nodes by clicking on canvas
- 🔗 Add edges between nodes by clicking two nodes
- 🧹 Delete nodes or edges
- 🔍 Zoom and pan support (scroll + right click drag)
- 🎨 DFS traversal animation with color-coded components
- 🧼 Reset zoom/pan instantly
- 📱 Responsive UI with a floating control panel

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS
- **Library:** [p5.js](https://cdnjs.com/libraries/p5.js)

## 🧑‍💻 How to Use

1. Clone this repository or download the HTML file.
2. Open `dfs.html` in any modern browser (Chrome recommended).
3. Use the buttons in the right-hand panel to:
   - **Add Node:** Click on canvas to place a new node.
   - **Add Edge:** Click two existing nodes to connect them.
   - **Run DFS:** Highlights the graph components using depth-first search.
   - **Delete:** Click the same node twice to delete it (and connected edges), or click two nodes to remove the edge between them.
   - **Reset Zoom:** Resets zoom level and pan offset.

## 🖱️ Controls

| Action           | Interaction         |
|------------------|---------------------|
| Add Node         | Click on canvas     |
| Add Edge         | Click two nodes     |
| Delete Node      | Double-click node   |
| Delete Edge      | Click two connected nodes |
| Pan              | Right-click + drag  |
| Zoom             | Mouse scroll        |
| Reset Zoom       | Click "Reset Zoom"  |

## 🎬 Demo

https://youtu.be/bAFIsWZ6wT8

## 🧪 Known Limitations

- No drag-to-move nodes (yet)
- DFS animation speed is fixed
- No saving/loading graph state

## 📜 License

This project is licensed under the MIT License. Feel free to fork and improve!
