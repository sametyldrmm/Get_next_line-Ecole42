# get_next_line Project

The get_next_line project is a challenging assignment aimed at helping students develop their skills in reading from a file line by line in the C programming language. The goal of the project is to create a function that reads a single line from a file and returns it to the calling function. The function should be able to handle the End of File (EOF) condition, as well as implement proper dynamic memory management to ensure efficient use of memory. The project is a great opportunity for students to demonstrate their understanding of file handling and memory management in C programming.

## Objectives
- Read lines from a file
- Return the next line after each read operation
- Take into account the EOF (End of File) condition
- Implement dynamic memory management

## Requirements
- Basic knowledge of C programming
- Understanding of file manipulation and handling
- Familiarity with the concepts of static and dynamic libraries

## Project Structure
The project will include the following files:
- `get_next_line.h`: This file contains the function declaration and macros used in the project.
- `get_next_line.c`: This file contains the implementation of the `get_next_line` function.
- `main.c`: This file includes test functions to test the functionality of the `get_next_line` function.

## Testing
To test the project, follow these steps:
1. Clone or download the project from GitHub: `https://github.com/sametyldrmm/get_next_line`
2. Edit the main.c file
```
#include<stdio.h>
#include"get_next_line.h>

int main()
{
  printf("%s\n",get_next_line("deneme.txt");
}
```

3. Compile the project using the following command: `gcc main.c get_next_line.c get_next_line_utils.c`
4. Run the compiled program with the following command: `./get_next_line`

## Contributing
This project is open for contributions from anyone. If you find any bugs or have any suggestions for improvements, you can submit a pull request. Your contributions are highly appreciated and will help make the project better.
