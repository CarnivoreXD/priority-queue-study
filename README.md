# Project 5 Batch and Drain

## Student Information:

Guillermo Rojas<br>
Student ID: 008008657<br>
https://github.com/CarnivoreXD/priority-queue-study

## Collaboration & Sources:

This work is primarily my own. I used the following resources for learning, debugging, and comparison

I used geeksforgeeks, stackoverflow, and chatGPT to debug and compare my code when I was getting errors when trying to make trace files for the batch then drain

I used chatGpt to diagnose an error where the output was not being saved as a csv result and troubleshot it that way.

I had claude help me understand how to modify the trace generator to produce both profiles because I was running into issues trying to copy the code from the huffman code.


## Implementation Details:




## Testing & Status: 

The way I tested is that I copied the scrips from the directory on blue onto project and copied the sample inputs into my input_output directory using the script provided. I then ran a <br>
bash compile_and_test.bash all_texts.txt
for all the sample texts and got tokens with no output being shown which showed clearly that there was no issues with my code. The tokens then were place in the input_output directory after being compared.Used bash compile_and_test_project3_part2.bash to test 11 input files. Results:
All 11 files tested successfully<br>
Both .tokens and .freq outputs matched references perfectly<br>
Summary: 22 matches, 0 differences<br>
All output files (.tokens, .freq, .hdr, .code) generate correctly for all test cases from small files (14 tokens) to large files (35,484 tokens)