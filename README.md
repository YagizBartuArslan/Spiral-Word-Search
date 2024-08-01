# Spiral Word Search

This project is a Spiral Word Search program written in C++. It reads an NxN matrix from a file and searches for specified words within the matrix using a spiral search pattern.

## Author

Yağız Bartu Arslan - Junior Computer Science & Engineering Student at Sabanci University

## Date

Written on 17.10.2023

## Description

The program reads a matrix of uppercase alphabetical characters from a file and searches for words within the matrix using a spiral search pattern. The program ensures that the input file is in the correct format and outputs the words found in the matrix.

## Features

- **Input Validation**: Checks if the matrix is in the correct NxN format and contains only uppercase alphabetical characters.
- **Spiral Search**: Searches for words in the matrix using a predefined spiral pattern.
- **Output**: Outputs the words found in the matrix.

## Files

- `main.cpp`: The main file containing the implementation of the program.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/YagizBartuArslan/spiral-word-search.git
    cd spiral-word-search
    ```

2. **Compile the code**:
    ```sh
    g++ -o spiral_search main.cpp
    ```

3. **Run the executable**:
    ```sh
    ./spiral_search
    ```

4. **Provide the input file**:
    - The program will prompt you to enter the name of the file containing the matrix and words to be searched.

### Input File Format

1. **First Line**: An integer N, representing the size of the NxN matrix.
2. **Next N Lines**: Each line contains exactly N uppercase alphabetical characters.
3. **Next Line**: An integer representing the number of words to be searched.
4. **Remaining Lines**: Each line contains a word to be searched in the matrix.

Example:
5
ABCDE
FGHIJ
KLMNO
PQRST
UVWXY
3
ABC
FGH
PQR

## Example Usage

1. **Sample Input File** (`sample_input.txt`):
    ```
    5
    ABCDE
    FGHIJ
    KLMNO
    PQRST
    UVWXY
    3
    ABC
    FGH
    PQR
    ```

2. **Run the Program**:
    ```sh
    ./spiral_search
    ```

3. **Program Output**:
    ```
    Enter the name of the file
    sample_input.txt
    3 Words are Found:  ABC FGH PQR
    ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.


