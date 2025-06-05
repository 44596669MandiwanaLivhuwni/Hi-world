# Hi-world
This repository is for practicing the GitHub flow
My name is  Livhuwani Mandiwana
#include <iostream>

int main() {
  std::cout << "Hello, World!" << std::endl;
  return 0;
}
Explanation:
#include <iostream>: This line includes the iostream library, which provides input and output functionalities.
int main(): This is the main function where the program execution begins. Every C++ program must have a main function. 
std::cout << "Hello, World!" << std::endl;: This line prints the text "Hello, World!" to the console.
std::cout is the standard output stream object.
<< is the insertion operator, used to send the output to the stream.
std::endl inserts a newline character, moving the cursor to the next line.
return 0;: This line indicates that the program has executed successfully and returns an exit code of 0.
How to compile and run:
Save the code in a file named hello.cpp.
Open a terminal or command prompt.
Compile the program using a C++ compiler (like g++):
Code

    g++ hello.cpp -o hello
Run the executable.
Code

    ./hello  # On Unix-like systems
    hello    # On Windows
This will output "Hello, World!" to the console.
