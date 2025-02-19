# chuffman

Huffman Coding in C
This project implements Huffman Coding from scratch in C for educational purposes. It demonstrates lossless data compression using an Encoding Tree and Decoding Tree to efficiently compress and extract information.

The program is designed to work seamlessly with ASCII text files, making it ideal for learning about entropy encoding, priority queues, and binary tree structures in data compression.

Features
Implements Huffman Encoding to reduce file size.
Supports Huffman Decoding to reconstruct the original text.
Uses a frequency-based priority queue to build the encoding tree.
Generates a codebook containing Huffman codes for each character.
Supports custom input/output filenames with default options for convenience.
Efficient and lightweight, making it suitable for educational and practical applications.
This project provides a hands-on learning experience in data compression algorithms, helping students and enthusiasts understand how text compression works at a fundamental level.

# usage
Open Command Prompt :
    1.Navigate to the folder where your chuffman code files are located. For example
    
    cd C:\path\to\your\chuffman

# Compile the Code
    Use the GCC compiler to compile the code. Run the following command:
    gcc *.c -o chuffman -Wall'''
   What happens here:

    gcc is the C compiler.
    *.c compiles all .c files in the folder.
    -o chuffman specifies the output file name as chuffman.
    -Wall enables warnings to help catch potential issues.

# Run the Program
3.For Huffman Encoding
-To compress a file (e.g., book.txt), use:

    chuffman -e book.txt -b codebook.txt -o encoded.txt

-Using default filenames: If you don’t provide -b or -o, the program uses:

    chuffman -e book.txt

# For Huffman Decoding

To decode a file (e.g., encoded.txt), use:

    chuffman -d encoded.txt -b codebook.txt -o origin.txt

-Using default filenames: If you don’t provide -b or -o, the program uses:

    chuffman -d encoded.txt

All command :- <br>

    gcc *.c -o chuffman -Wall
    
    ./chuffman -e book.txt -b codebook.txt -o encoded.txt
    
    ./chuffman -e book.txt
    
    ./chuffman -d encoded.txt -b codebook.txt -o origin.txt
    
    ./chuffman -d encoded.txt

#Auther 
[Aditya Birajdar](https://github.com/ifskelton69)
