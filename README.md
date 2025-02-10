# Elixir Bug: Modifying a List During Enum.each

This repository demonstrates a common Elixir error: attempting to modify a list during an `Enum.each` iteration.  Because Elixir uses immutable data structures, the changes within the `Enum.each` loop do not persist in the original list.

The `bug.exs` file shows the incorrect approach. The `bugSolution.exs` file demonstrates the correct way to solve this issue using `Enum.filter`.

**To run the code:**

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `elixir bug.exs` and `elixir bugSolution.exs` in your terminal.
