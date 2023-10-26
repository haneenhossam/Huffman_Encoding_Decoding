# Huffman_Encoding_Decoding
A Huffman code is a sort of optimum prefix code that is used to compress data. The Huffman encoding and decoding methodology is also lossless, which means that no information is lost when data is compressed to make it smaller. The Huffman algorithm assigns codes to each character based on its associated frequency. The Huffman code may be any length and does not require a prefix. Hence, this binary code can be viewed as a binary tree, with each encoded character stored on leafs.

There are mainly three major parts in Huffman encoding/decoding:
1. Build a Huffman tree from input data.
2. Encode the input data by traversing the Huffman tree and assigning codes to characters.
3. Decode the data using the encoded data and tree as an input.

# More explanation
<img src="https://github.com/haneenhossam/Huffman_Encoding_Decoding/assets/67436191/81adfac8-0c21-4e66-a2de-dfe27b58f965" width = "45%" height = "30%"><img src="https://github.com/haneenhossam/Huffman_Encoding_Decoding/assets/67436191/f79c4627-a50c-49b3-829d-85e4d5295297" width = "45%" height = "30%">


# Recourses
Here are three main resources for better understanding:
- Visualization of building Huffman tree: https://people.ok.ubc.ca/ylucet/DS/Huffman.html
- https://www.geeksforgeeks.org/huffman-coding-greedy-algo-3/?ref=lbp
- https://www.geeksforgeeks.org/huffman-decoding/?ref=lbp
