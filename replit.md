# C Data Structures Lab (TDA Lista y Pila)

## Overview
An educational C lab assignment focused on implementing Abstract Data Types (ADTs) — specifically a List (TDA Lista) and a Stack (TDA Pila). Students implement five exercises in `exercises.c`.

## Tech Stack
- **Language:** C (compiled with gcc)
- **Build:** `gcc -g test.c -Wall -Werror -o a.out`
- **No frontend or backend server** — pure command-line project

## Project Structure
- `exercises.c` — Student implementation file (edit this to complete exercises)
- `arraylist.c` / `arraylist.h` — List ADT implementation
- `stack.h` — Stack ADT (header-only, built on top of the List)
- `test.c` — Test suite (do not modify)
- `test.sh` — Compile, run tests, and optionally push to GitHub

## Workflow
- **Run Tests** — Runs `bash test.sh` which compiles and executes all tests

## How to Use
1. Edit `exercises.c` to implement the five functions
2. Run the "Run Tests" workflow to compile and check your progress
3. Tests show OK/FAILED per exercise and a total_score out of 70

## Exercises
1. `crea_lista` — Create a list populated with integers 1–10
2. `sumaLista` — Sum all integers in a list
3. `eliminaElementos` — Remove all occurrences of an integer from a list
4. `copia_pila` — Copy elements from one stack to another in order
5. `parentesisBalanceados` — Check if brackets/parentheses in a string are balanced
