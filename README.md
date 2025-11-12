# FILE-COMPRESSION-PROGRAM
*What does the Project do?

This project implements file compression and decompression using the concept of Huffman Coding.
The program reduces the size of a given input file by encoding frequently occurring characters with shorter binary codes and can later decompress it back to its original form.

*Features:

1.Compresses a text file into a smaller binary file.
2.Decompresses the compressed file back to its original form.
4.Handles both small and large text files.

*Files Included:

1. README.md	- Documentation file explaining the project.
2. ffrequency.c - Takes the input , reads the file and return the frequency of each character.
3. keys.c - Generates the Hufmann code for each character using tress.
4. encoding.c - It encodes the file using the given Huffman code.
5. input.txt(to be entered by the user)	- Example input file to be compressed.
6. compressed.bin - Output compressed file.
7. decompress.c - Restore the file back to the original form.
8. decompressed.txt	- File obtained after decompression.

*How to Run:

Step 1: Compile the code
Open your terminal and compile the C program:
gcc ffrequency.c keys.c encoding.c decompress.c -o compress

Step 2: Run for compression and decompression
Run the executable and provide the input file name:
./compress compress input.txt

*Input Format:

Input: A normal text file (e.g., input.txt) containing text or data to compress.
Example Input (input.txt):
hello world

*Output Format:(see again)

Compressed file: A binary file  representing the encoded data(eg compressed.bin).
Decompressed file: A text file identical to the original(eg decompressed.txt).
Example Output (after decompression):
hello world

*Example Run:

Input file size: 12 bytes
Compressed file size: 7 bytes

*Concepts Used:

1.Frequency counting of characters.
2.Building Huffman Tree.
3.Generating binary codes.
4.Bit-level file writing.
5.Decoding using the Huffman tree.

*Improvements in future.
1.Include compression ratio.
2. Add support for multiple file types.

*Makers:
Mahak Agrawal(B25CS1036).
Kaushiki Mukherjee(B25BB1016).
Preeti Saini(B25EE1030).
Gourav Saini(B25CH1017).
BhosAle Ritu Anil(B25ME1013).

