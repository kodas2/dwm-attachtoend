# dwm-attachtoend
A patch for dwm version 6.1 which edits the order in which new windows are placed.

The current behaviour:
+-----------+
|           |
|     1     |
|           |
+-----------+

+-------+---+
|       |   |
|   2   | 1 |
|       |   |
+-------+---+

+-------+---+
|       | 2 |
|   3   +---+
|       | 1 |
+-------+---+

New behaviour:
+-----------+
|           |
|     1     |
|           |
+-----------+

+-------+---+
|       |   |
|   1   | 2 |
|       |   |
+-------+---+

+-------+---+
|       | 2 |
|   1   +---+
|       | 3 |
+-------+---+
