# Lab 1 – AI Problem Formulation & Intelligent Problem Solving

## Objective

The objective of this lab is to understand the fundamentals of Artificial Intelligence problem formulation and intelligent problem-solving techniques.

---

## Experiments

### 1. Vacuum Cleaner Problem

#### Problem Statement

A simple reflex agent operates in an environment consisting of two rooms, **A** and **B**. Each room can either be **Clean** or **Dirty**.

The agent observes the current state of the room and performs an appropriate action.

#### Production Rules

1. If the current room is **Dirty** → **Suck**
2. If the current room is **A** and Clean → **Move Right**
3. If the current room is **B** and Clean → **Move Left**

#### Learning Outcome

This experiment demonstrates how a simple reflex agent makes decisions based only on the current percept without maintaining any internal memory.

---

### 2. Water Jug Problem

#### Problem Statement

Given two jugs with capacities **X** and **Y**, the objective is to measure exactly **Z** litres of water using the available operations.

#### Operations

- Fill a jug completely.
- Empty a jug completely.
- Pour water from one jug into the other until either the source jug is empty or the destination jug is full.

#### Solvability Condition

The problem is solvable when:

```text
Z ≤ max(X, Y)
