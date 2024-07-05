# Plag-Detector-
Technical Description for complex.cpp in README.md
complex.cpp
This program is designed to compare the similarity between two text files using the Jaccard similarity coefficient. The main steps involved in the process include tokenizing the text, forming sets of tokens, and computing the Jaccard similarity between these sets. The Jaccard similarity coefficient is a measure used to determine the similarity between two sets. It is defined as the size of the intersection divided by the size of the union of the sets.

Features
Tokenization: The program breaks down the input text files into individual tokens. Tokens are alphanumeric sequences separated by non-alphanumeric characters.
Set Formation: Converts the list of tokens into unordered sets for comparison.
Jaccard Similarity Calculation: Computes the similarity between two sets of tokens from the input files.
Usage
Compile the program:
sh
Copy code
g++ -o complex complex.cpp
Run the program:
sh
Copy code
./complex
Input the names of the two files to be compared when prompted.
Example
Suppose you have two files, file1.txt and file2.txt, containing some code or text. The program will prompt you to enter the names of these files and will then output the Jaccard similarity coefficient indicating the similarity between the contents of the two files.
