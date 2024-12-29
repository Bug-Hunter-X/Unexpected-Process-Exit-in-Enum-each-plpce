# Elixir Enum.each Exception Handling

This example highlights a potential issue when using `Enum.each` in Elixir.  If an exception occurs within the anonymous function, the process will abruptly exit. This behavior can lead to unexpected crashes and make debugging more challenging.

The `bug.ex` file demonstrates the problem. The `bugSolution.ex` file provides a solution using `Enum.try_each` for better error management.