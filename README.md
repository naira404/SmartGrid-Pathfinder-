# 🐝 SmartGrid-Pathfinder

A path planning project using swarm intelligence algorithms—**ABC (Artificial Bee Colony)**, **PSO (Particle Swarm Optimization)**, 
and **ACO (Ant Colony Optimization)**—
to solve a grid navigation challenge with obstacles and collectible items.

---

## 📌 Table of Contents

* [📖 Project Overview](#-project-overview)
* [🧠 Algorithms Used](#-algorithms-used)
* [🧪 How It Works](#-how-it-works)
* [🖥️ How to Run](#-how-to-run)
* [👨‍💻 Team Members](#-team-members)

---

## 📖 Project Overview

The project simulates a 20x20 grid where:

* The robot must move from a **start** point to a **goal**.
* Along the way, it must **collect items** and **avoid obstacles**.
* The task is solved using three swarm algorithms, each trying to optimize path length and item collection.

---

## 🧠 Algorithms Used

1. 🐝 **Artificial Bee Colony (ABC)**
   Inspired by the foraging behavior of bees to find optimal paths.

2. 🐜 **Ant Colony Optimization (ACO)**
   Uses pheromone trails to simulate how ants discover paths to food.

3. 🐦 **Particle Swarm Optimization (PSO)**
   Mimics the movement of flocks to search for optimal solutions.

---

## 🧪 How It Works

* The environment is a **2D grid** (20x20) with:

  * Randomly placed **obstacles**.
  * Randomly placed **items** to be collected.
* Each algorithm generates and evaluates **multiple paths** based on:

  * Path **length**.
  * Number of **items collected**.
  * Whether the **goal is reached**.

## 🖥️ How to Run

1. Open the provided `.ipynb` file in **Google Colab** or **Jupyter Notebook**.
2. Run all cells in order.
3. Watch how each algorithm explores and collects items!


## 👨‍💻 Team Members

* 👩‍💻 Naira Ibrahim
* 👨‍💻 Eman Hisham
* 👩‍💻 Doha Sayed
  


