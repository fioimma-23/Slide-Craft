# 🧩 Slide Puzzle Game

A classic **3x3 sliding tile puzzle** built with **HTML, CSS, and JavaScript**. Rearrange the tiles into order using as few moves as possible!

---

## 🎮 Features

- 🖱️ Drag-and-drop tile movement  
- 🔢 Numbered tile system (1–8 + blank)  
- 🔄 Turn counter to track player moves  
- 🎨 Clean blue-themed UI  
- 📱 Responsive layout for all devices

---

## 🚀 How to Play

1. Open `index.html` in your browser  
2. Drag tiles to the adjacent blank space  
3. Arrange tiles in the correct order: `1` to `8`  
4. Blank tile (`9`) should be in the **bottom-right corner**  
5. Try to finish the puzzle in the **fewest moves possible**

---

## 🕹️ Controls

| Input      | Action                                |
|------------|---------------------------------------|
| Mouse / Touch | Drag tile to adjacent empty space |
| Button     | "End Game" to stop current session    |

---
## 🛠️ Technical Overview

### 🧠 Game Logic
- Tiles are images numbered `1.jpg` to `9.jpg`.
- The `dragEnd` function checks tile adjacency and swaps them.

---

## 🔧 Customization

Change the default image tile arrangement by modifying:

```javascript
// Custom starting layout
var imgOrder = ["4", "2", "8", "5", "1", "6", "7", "9", "3"];

