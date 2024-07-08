# Advanced Algorithms Assignment: Applying Linear Programming

![Advanced Algorithms Logo](link-to-logo-image)

## Project Overview

This project involves applying linear programming to the satisfiability problem to obtain upper and lower bounds on the number of clauses that can be satisfied simultaneously. The implementation uses GLPK for solving linear programming problems and involves randomization techniques for generating variable assignments.

## Features and Capabilities

### Linear Programming
- **Modelling SAT Problem**: The project involves modelling the SAT problem as an integer linear program (ILP) with binary variables representing the assignment of variables and clauses.
- **Linear Relaxation**: Uses linear relaxation to obtain an upper bound on the number of satisfiable clauses.
- **GLPK Integration**: Utilizes the GLPK library for solving the linear programming problem.

### Randomization Techniques
- **Random Assignments**: Generates random variable assignments based on probabilities obtained from the linear relaxation solution.
- **Simulated Coin Flips**: Implements a coin flip function to create random assignments and evaluates the number of satisfiable clauses.

### Implementation Details
- **DIMACS CNF Format Handling**: Reads SAT instances from files in the DIMACS CNF format.
- **Efficient Data Structures**: Uses a 2-dimensional array to store the SAT instance and perform computations.
- **Recursive Functions**: Implements recursive functions for operations like deleting items from the Trie structure.

### Performance Testing
- **Testing with Multiple Instances**: Evaluates the implementation using multiple SAT instances to ensure correctness and robustness.
- **Comparison of Results**: Provides both upper and lower bounds on the number of satisfiable clauses.

## Project Structure

\`\`\`plaintext
├── src
│   ├── satBounds3.c
├── README.md
\`\`\`

### satBounds3.c
Contains the main implementation for solving the SAT problem using linear programming and randomization techniques.

## Key Skills Demonstrated

### Software Engineering
- **Code Modularity**: Implementation is modular with well-defined functions for different tasks.
- **Code Readability**: Code includes comments and follows good practices for readability and maintainability.
- **Error Handling**: Robust handling of input and output operations, including reading from files and managing data structures.

### Algorithm Design
- **Linear Programming**: Application of linear programming to model and solve the SAT problem.
- **Randomization**: Use of randomization techniques to generate variable assignments and evaluate satisfiability.

### Testing and Validation
- **Comprehensive Testing**: Extensive testing with provided and additional SAT instances to validate the implementation.
- **Performance Analysis**: Analysis of the performance and correctness of the implementation.

## Installation and Usage

To run this project, you need to have a C compiler (e.g., gcc) and GLPK installed on your system. Clone the repository and compile the C file:

\`\`\`bash
git clone https://github.com/yourusername/advanced-algorithms-assignment.git
cd advanced-algorithms-assignment/src
gcc satBounds3.c -o satBounds3 -lglpk
\`\`\`

Run the program with a SAT instance file:

\`\`\`bash
./satBounds3 path_to_sat_instance.cnf
\`\`\`

## Author

Nikola Nikolov [nin6]  
Email: [Nin6@aber.ac.uk](mailto:Nin6@aber.ac.uk)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
