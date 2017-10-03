# Huffman-Coding

The first step in this project is to develop a program that generates Huffman codes.
Binary Heap, 4-way cache optimized heap, and Pairing Heap are the data structures evaluated for this project.
Once you have determined which data structure gives the best performance, finalize your Huffman code program using that data structure. The finalized Huffman code program will take as input a frequency table and output a code table.
Once the Huffman code program is finalized, you should proceed to write the encoder and decoder.

The encoder reads an input file that is to be compressed and generates two output files – the compressed version of the input file and the code table.
First step towards Huffman encoding is to build the frequency table for each value in input.
Use the data structure with best timing to build the Huffman code table.
Once the code table is built, it can be used to encode the original input file by replacing each input value by its code.

The decoder reads two input files - encoded message and code table.
The decoder first constructs the decode tree using the code table.
Then the decoded message can be generated from the encoded message using the decode tree.
The decoder takes two input files - encoded message and code table. File names will be given as command line arguments. The format of these files is the same as the output format of the encoder, so that the output files of the encoder program can be directly used by the decoder program.

