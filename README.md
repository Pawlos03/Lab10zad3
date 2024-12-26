# File Copy and Replace Spaces Project

## Description
This project reads a text file, replaces all spaces (`" "`) with hyphens (`"-"`), and writes the modified content to a new file. It uses Java's `try-with-resources` to ensure automatic resource management for file handling.

## Structure
1. **Class `FileCopyReplaceSpaces`**:
   - Contains the static method `copyFileAndReplaceSpaces`.
   - Reads a file line by line, replaces spaces with hyphens, and writes to the output file.
   - Handles potential `IOException` during file operations.

2. **Class `Main`**:
   - Defines the entry point of the program.
   - Provides paths for the input and output files and calls the method from `FileCopyReplaceSpaces` to perform the operation.

## Usage
1. Create an input file (e.g., `input.txt`) with the content you want to process.
2. Compile the Java files using:
   ```sh
   javac FileCopyReplaceSpaces.java Main.java
   ```
3. Run the program using:
   ```sh
   java Main
   ```
4. The output will be written to `output.txt` with spaces replaced by hyphens.

## Example
### Input (`input.txt`):
```
Hello World
Java Programming
```
### Output (`output.txt`):
```
Hello-World
Java-Programming
```

