# Project Goal 

The goal of this project was to reason about sequence alignment with affine gap penalty. 

To do this, I first wrote a program, `without_gap_affine` which implements the sequence alignment algorithm without affine gap penalties. 

Secondly, I wrote a program `with_gap_affine.py` which implements the sequence alignment algorithm with affine gap penalty. The scoring function for this is as follows:

• Match of identical nucleotides: +1
• Match of non-identical nucleotides: -2
• Gap open: -5
• Gap extension: -1

## To run the code 

1. copy the first sequence you want to run into the seq1.fa file. Paste the sequence in the second line under the NAME. 

2. Copy the second sequence you want to run into the seq2.fa file. Paste the sequence in the second line again under the NAME. 

PS. In both cases, it must be pasted under the name, in the second line, or the program will not run. 

3. Type either python3 command in the terminal window.

python3 without_gap_affine.py 

python3 with_affine_gap.py 

You will see the output of the score and the alignment in the terminal window when using the algorithm with or without affine gap. 
