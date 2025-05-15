# 📦 push_swap

> A stack-based sorting project using a quicksort-inspired algorithm.

## 📌 Description

**push_swap** is a 42 School project that sorts a stack of integers using a limited set of operations and two stacks: `A` and `B`. The goal is to sort stack `A` with the fewest possible instructions using only push, swap, rotate, and reverse operations.

This implementation is powered by the **quicksort algorithm**, adapted to work within the push_swap constraints. It emphasizes algorithmic efficiency, memory control, and operation optimization.

## ⚙️ Allowed Instructions

- `sa`, `sb`, `ss` — swap the top elements
- `pa`, `pb` — push from one stack to the other
- `ra`, `rb`, `rr` — rotate stack up
- `rra`, `rrb`, `rrr` — reverse rotate stack down

## 🚀 How It Works

The algorithm works by recursively dividing the stack into chunks, selecting pivots, and using quicksort-style partitioning while relying on the allowed instructions to move elements between stacks.

## 🧪 Example

```bash
./push_swap 4 2 5 3 1
# Output:
pb
pb
sa
pa
pa
ra
ra

