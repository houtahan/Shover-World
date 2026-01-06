Shover-World
=============

Lightweight implementation of the Shover game environment and a small GUI for
running and testing AI agents.

Quick start
-----------
Requirements: Python 3.8+ and the dependencies in `requirements.txt`.

1. Install dependencies:

    pip install -r requirements.txt

2. Run the GUI / demo:

    python main.py

AI solver
---------
- Implement your A* agent and heuristic in `AstarTemplate.py`.
- The environment and GUI will import and run your agent when `main.py` is
   executed.
- A simple example agent is provided in `simpleAgent.py` — to run it, replace
   the solver import in `main.py` with the `simpleAgent` module (the file name
   is `simpleAgent.py`).

Maps and assets
---------------
- Maps are stored in the `maps/` folder (plain text map files). Try the
   included maps: `maps/map1.txt`, `maps/map2.txt`, `maps/map3.txt`.
- Graphics and other resources live in the `assets/` folder. Placeholder
   textures are used if images are missing.

Project layout
--------------
- `main.py` — entry point / demo runner for the GUI and agent playback
- `gui.py` — GUI and rendering code
- `environment.py` — environment implementation and game rules
- `AstarTemplate.py` — agent template (implement A* and your heuristic here)
- `simpleAgent.py` — example agent to study or run
- `maps/`, `assets/`, `requirements.txt` — data and dependencies

Notes
--------------------
- To evaluate or submit an agent, modify only `AstarTemplate.py` (or add a
   new agent module). Avoid changing core environment or GUI files.
- You are free to add more maps to `maps/` for testing.

Enjoy experimenting with pathfinding and heuristics!