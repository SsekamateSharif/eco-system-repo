# Agent-Based Simulations in Python

This repository contains a set of **agent-based simulation models** implemented in Python. Each model demonstrates how interactions between simple agents can lead to emergent system-level behavior. All simulations are visualized using **histograms** to analyze the resulting distributions and dynamics.

---

## Repository Structure

```
.
├── Money_model.py      # Wealth exchange simulation
├── ecosystem.py        # Predator–prey ecosystem simulation
├── cleaning.py         # Robot vacuum cleaner simulation
└── README.md           # Project documentation
```

---

## Simulations

### Money Model (`Money_model.py`)

This simulation represents a simplified economic system in which agents exchange wealth.

* Agents start with an initial amount of money.
* At each interaction, money is exchanged between agents according to predefined rules.
* The total amount of money in the system is conserved.
* The simulation demonstrates how wealth distribution evolves over time.

**Visualization:**

* Histograms showing the distribution of wealth among agents.

---

### Ecosystem Model (`ecosystem.py`)

This simulation models a basic predator–prey ecosystem.

* Prey agents move within the environment and can be consumed by predators.
* When a predator consumes a prey, the prey loses its life.
* For each prey consumed, the predator gains one unit of energy.
* Predator survival depends on accumulated energy.

**Visualization:**

* Histograms illustrating population and energy distributions over time.

---

### Robot Vacuum Cleaner Model (`cleaning.py`)

This simulation models a robot vacuum cleaner operating in a room with dirty tiles.

* The environment consists of tiles that can be clean or dirty.
* The robot moves through the environment following simple rules.
* When the robot encounters a dirty tile, it cleans it.
* The simulation evaluates cleaning efficiency over time.

**Visualization:**

* Histograms showing the number of clean and dirty tiles during the simulation.

---

## Requirements

* Python 3.x
* Required libraries:

  * numpy
  * matplotlib

Install dependencies using:

```bash
pip install numpy matplotlib
```

---

## Running the Simulations

Each simulation can be run independently:

```bash
python Money_model.py
python ecosystem.py
python cleaning.py
```

Each script runs the simulation and displays the corresponding histograms.

---

## Purpose

This repository is intended for educational and experimental purposes, particularly for studying agent-based modeling, complex systems, and emergent behavior.

---

## License

This project is open-source and available for educational and research use.
