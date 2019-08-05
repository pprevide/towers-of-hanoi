

# Towers of Hanoi 

This project demonstrates the solutions for a 3-peg game of Towers of Hanoi, for any pre-specified number of starting disks.

The rules of the game can be found at its [Wikipedia page](https://en.wikipedia.org/wiki/Tower_of_Hanoi).  The rules can be summarized as follows:

- One disk can be moved per turn.
- A disk is eligible to be moved if it is at the top of a stack or alone on a peg. 
- A disk eligible to be moved can be placed on top of another stack or along onto a peg different from the one on which it started the move, subject to the next rule.
- No larger disk can be placed on top of a smaller disc.

## Recursion

The Towers of Hanoi game represents a problem that is suitable for a recursive solution.  Recursion is convenient when a solution to a problem can be defined in terms of a solution to a smaller version of the same problem.


## Usage

To run this project, version 7 or higher of Java is required.  download the jar file located in the out directory of this repository and execute the jar file from the command line as follows:

```bash
java --jar Towers.jar
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
