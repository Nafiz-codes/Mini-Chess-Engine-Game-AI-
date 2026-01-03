# 🧠 Mini Chess Engine

A lightweight, educational chess engine built from scratch — blending ideas from minimal engines like Sunfish and high-performance designs like Stockfish. This project is a sandbox for exploring chess AI fundamentals: position representation, move generation, search algorithms, evaluation metrics, and optional optimizations.

## 🚀 Features

- ♟️ Board representation and full legal move generation

- 🔍 Search algorithm (Minimax / Alpha-Beta pruning or alternatives)

- 📊 Position evaluation function

- 🧩 UCI (Universal Chess Interface) support

- 🔄 Optional enhancements:

 -Iterative deepening

 -Transposition table

 -Move ordering heuristics

 -Simple parallelization

💡 Inspired by clean, simple engines like Sunfish (a Python chess engine in ~111 lines) and pro engines like Stockfish, this engine is designed for learning and experimentation.
GitHub
+1

## 🛠️ How It Works (Overview)

At a high level, chess engines perform the following steps:

### 1. Board Representation

Maintain an internal state of the chess position.

### 2. Move Generation

Generate all legal moves for the current position.

### 3. Game Tree Search
Explore future positions using an algorithm like minimax with alpha-beta pruning to determine the best move.

### 4. Evaluation Function
Score positions to decide which side is better. More advanced engines like Stockfish use complex heuristics and even neural network evaluations.
YouTube
+1

🎥 For a solid conceptual intro to building chess engines from scratch, check out the chess engine development video linked in community discussions — it walks through essential concepts and implementation techniques.
Codeforces

## 📦 Getting Started

### Prerequisites

- Python / C++ / your chosen language

- Standard development tooling (compiler / interpreter)

- UCI-compatible chess GUI (optional)

### Installation

### 1. Clone your repo

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME
cd YOUR_REPO_NAME
```

### 2. Run your engine

```bash
#For Python
python engine.py
```

### 3. Optional: Connect to a UCI GUI
Use Arena, Cute Chess, or Lichess local setup to connect your engine via UCI.

## 🧪 Example Output

```bash
Position: Starting
Searching depth 1…
Best move: e2e4 (score: +0.23)
Nodes: 12345
Time: 0.05s
```

## 📐 Project Structure
```bash
/
├── engine.py               # Core search & evaluation logic
├── board.py                # Board representation & move generator
├── uci.py                  # UCI interface implementation
├── tests/                  # Unit tests
├── README.md
└── LICENSE
```

## 🧠 Understanding Key Concepts

| Component | Description |
|----------|-------------|
| **Board Representation** | Internal data structure that stores piece positions and game state |
| **Move Generation** | Generates all legal moves from a given position |
| **Search Algorithm** | Explores future positions using Minimax / Alpha-Beta pruning |
| **Evaluation Function** | Assigns a numerical score to a board position |
| **Move Ordering** | Improves search speed by exploring promising moves first |
| **Transposition Table** | Caches previously evaluated positions to avoid recomputation |
| **UCI Interface** | Allows the engine to communicate with chess GUIs |


These concepts are foundational in engines like Stockfish and simplified implementations such as Sunfish.
YouTube

## 🧩 Contributions

Contributions are welcome! Suggestions include:

- Adding more advanced move ordering

- Integrating a simple neural evaluation component

- Benchmark tests versus Sunfish or baseline engines

## 📚 Resources

- Sunfish — elegant minimalist Python engine: https://github.com/thomasahle/sunfish

- Stockfish — open source world-class UCI engine: https://github.com/official-stockfish/Stockfish

- Chess Engine Tutorials — building and understanding engines 
Codeforces

## 📝 License

This project is licensed under the MIT License — see the LICENSE file for details.
