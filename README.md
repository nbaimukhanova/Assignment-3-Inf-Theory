# Assignment-3-Inf-Theory
Input: “Text.txt” file and the result from Part 1. 
Goal: Encode the text from the “Text.txt” file using Huffman algorithm with  probabilities from Part 1.  

1. Symbols with probabilities sorted in descending order (round to three decimal places). Please  also add the notations for whitespace, new line, tab and etc. in order to distinguish them. 
2. Build Shannon-Fano or Huffman code tree based on the given list with probabilities. Include  all intermediate steps. 

3. Create the list with symbols and their codewords in descending order starting from the most  frequent symbol to the least frequent symbol. Perform a traversal of tree to determine all  codewords. 

4. Scan text again, output a sequence of binary digits using the Shannon-Fano or Huffman  codes, and save in a new .txt file. 

5. After these replacements are made, calculate a data compression ratio: number of bits in  the original text / the number of bits in the compressed text, and average code length = ∑ ( frequencyi x code lengthi ) / ∑ ( frequencyi ).  
Note: ASCII uses 1 byte to represent a letter or a punctuation mark. 
