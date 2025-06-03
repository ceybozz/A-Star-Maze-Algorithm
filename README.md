# ⭐ A* Maze Solver

A Python project that generates a maze and solves it using the A* (A-Star) pathfinding algorithm with visualization powered by `pyamaze`.

## 🎯 Goal

Find the shortest path from the bottom-right corner of a generated maze to the top-left corner using A* algorithm.

## 🧠 Algorithm Details

The A* algorithm uses the Manhattan distance as a heuristic to efficiently find the shortest path while considering both distance traveled and estimated remaining distance.

## 🧱 Maze Format

- Maze is generated using `pyamaze`
- Start point: bottom-right corner (rows, cols)
- Goal point: top-left corner (1, 1)

## 🚀 How to Run

1. Install `pyamaze` if not already installed:
   ```bash
   pip install pyamaze
   ```

2. Run the script:
   ```bash
   python A_Star.py
   ```

3. A visual maze will appear. The agent will trace the shortest path calculated by A*.

## 📁 Project Files

- `A_Star.py`: Main implementation
- Auto-generated maze with visual trace
- Uses Manhattan distance as heuristic

## 📌 Future Enhancements

- Add GUI for custom maze size
- Allow loading custom mazes
- Add support for different heuristics (Euclidean, Diagonal)

## 📝 License

MIT © Your Name
