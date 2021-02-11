# week 02: stacks + intro to runtime analysis

<center>
<img width=60% src=tests2.jpg />
</center>

## Lecture

1. announcements
    1. great job using github issues
    1. there's no need to submit a pull request with homework assignments

1. first "actual computer science" instead of "programming"/"engineering"

1. key vocabulary
    1. abstract data types (ADTs)
        1. defines an interface
        1. no implementation details
    1. data structure
        1. defines an interface
        1. includes implementation details
    1. informally, ADTs are also called data structures

1. stack ADT, list data structure
    1. in python, always implemented using lists
    1. interface:
        1. `push`: add something on top; in python, we use the `append` method
        1. `pop`: take something off the top
    1. balanced parenthesis algorithm
        1. key technical interview question
    1. Reference: [textbook chapter 4](https://runestone.academy/runestone/books/published/pythonds/BasicDS/toctree.html)
        1. The textbook has their own library with a specially designed `Stack` object
        1. In the real python world, everyone just uses the `list` type for stacks,
           so that's what we'll use in this course

1. pytest library
    1. Install with the command:
       ```
       $ pip3 install pytest
       ```
    1. Run all tests in the file `tests/test_main.py` with:
       ```
       $ python3 -m pytest tests/test_main.py
       ```
    1. If you don't include a filename, pytest will test all the files.
       You should test your extra credit with the command
       ```
       $ python3 -m pytest
       ```
    1. If you use the `-x` flag, then pytest will stop after the first error.
       This is useful for development.
       If you want to skip a test case and stop after the second, use the argument `--maxfail 2`.
       The `-x` flag is a shortcut for `--maxfail 1`.

1. runtime analysis
    1. big O/Omega/Theta notation

**Pre-lecture work:**

1. print the `big-o.pdf` file 

## Lab

TBA
