# JFK ASCII Art Generator

## Project Overview
This project is a Python-based ASCII art generator that reconstructs a detailed portrait of John F. Kennedy. The unique aspect of this project is that it adheres to strict academic constraints: it uses **no external image processing libraries** (like PIL, OpenCV, or NumPy). Instead, the image generation relies entirely on fundamental programming concepts: **Nested Loops** and **Conditional Statements**.

## Features
* **Zero Dependencies:** Runs on standard Python 3 without the need to install `pip` packages.
* **Algorithmic Logic:** Uses a Run-Length Encoding (RLE) technique to store image data efficiently within the code.
* **Pure Logic:** Demonstrates how to manipulate strings and lists using only control flow statements.

## How It Works
Since reading raw image files directly (.jpg/.png) usually requires external libraries, this program uses pre-analyzed data stored as a "List of Lists" directly in the source code.

1.  **Data Structure:** The image data is stored as a list of tuples in the format `(Count, Symbol)`.
    * *Example:* `(10, '#')` acts as an instruction to "print the # character 10 times."
2.  **Reconstruction Logic:**
    * **Loop 1 (Rows):** Iterates through the main list to process the image line by line.
    * **Loop 2 (Segments):** Iterates through the tuples in each row.
    * **Loop 3 (Drawing):** A strictly loop-based approach iterates `Count` times to build the string for that row.
    * **Condition:** A conditional check (`if count > 0`) ensures valid data processing.

## How to Run
1.  Ensure you have Python 3.x installed on your system.
2.  Save the project code as `main.py` (or `jfk_ascii.py`).
3.  Open your terminal or command prompt.
4.  Navigate to the folder containing the file.
5.  Run the command:
    ```bash
    python main.py
    ```

## Requirements
* Python 3.x
* No external libraries required.

## Student Details
* **Name:** Abhishek Kumar
* **Class:** 3A
* **Subject:** Computer Science / Python Programming
