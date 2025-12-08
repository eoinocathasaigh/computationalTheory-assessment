# computationalTheory-assessment
A repo for my 4th year computational theory assesment

## Introduction
This repository demonstrates core concepts in computational theory relevant to implementing SHA-256, including:

- Implementing binary operations and methods (AND, OR, XOR, NOT)
- Bit shifting and rotations (left/right shifts, circular rotations)
- Factorials and cube roots (algorithmic computation and numeric methods)
- Message padding (preparing messages for hashing according to the spec)
- Message hashing (design and implementation of hash functions, focusing on SHA-256)

## Files
- `problems.ipynb`: A Jupyter notebook containing the implementations and explanations of the various computational theory problems.
- `README.md`: This file, providing an overview of the repository and its contents.
## Usage
To run the code, ensure you have Python and Jupyter Notebook installed. Open the `problems.ipynb` file in Jupyter Notebook and execute the cells to see the implementations and results

## Concepts Covered
- <b>Binary Operations</b>: Understanding and implementing basic binary operations such as AND, OR, XOR, and NOT.
- <b>Bit Shifting</b>: Techniques for shifting bits left or right within a binary representation e.g. left shift (<<) and right shift (>>) in their apporpriate methods.
- <b>Factorials & Cube Roots</b>: Calculating factorials and cube roots, which are fundamental in various algorithms.
- <b>Message Padding</b>: Implementing message padding techniques such as those used in SHA-256 i.e. appending a single '1' bit, followed by '0' bits, and finally the length of the original message.
- <b>Message Hashing</b>: Creating hash functions to securely represent data, specifically focusing on SHA-256
- <b>Password Hashing</b>: Demonstrating methods for cracking hashed passwords using dictionary attacks and understanding the vulnerabilities of weak passwords.

## Setup Instructions
1. Clone the repository to your local machine using
    ```git clone https://github.com/yourusername/computationalTheory-assessment.git```
2. Navigate to the project directory:
   ```cd computationalTheory-assessment```
3. Install the required dependencies (if any) using pip:
   ```pip install -r requirements.txt```
4. Open the Jupyter Notebook:
   ```jupyter notebook problems.ipynb```
5. Run the cells in the notebook to explore the implementations and explanations of the computational theory problems.

## Solution Structure
Each problem is structured in the notebook with the following format:
1. **Problem Statement**: A brief description of the problem being addressed, highlighting the key concepts involved.
2. **Implementation**: I provide an explanation of the methods involved in solving or implementing the solution, highlighting any important functions or algorithms used e.g. using `sympy.isprime()` to check for prime numbers.
3. **Code Sections**: Following an explanation of methods the actualy solution/implementation code is provided in code cells, sometimes divided into multiple cells when I use things such as Utility or helper functions as seen in problem 1, where they can be used in later problems.

## Conclusion
This repository is meant to serve as a guide or demonstration of key computational theory concepts, particularly in relation to the secure hash algorithm and the concepts it highlights like hashing. It provides practical implementations and explanations to help understand these fundamental topics in computer science as well as my understanding of them.