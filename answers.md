# CMPS 2200 Recitation 6
## Answers

**Name:** Reid Miller

Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File         | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt       | 1340                | 826            | 1:1.62

alice29.txt  | 1039367             | 676374         | 1:1.54

asyoulik.txt | 876253              | 606448         | 1:1.44

grammar.lsp  | 26047               | 17356          | 1:1.50

fields.c     | 78050               | 56206          | 1:1.39


For every text, the Huffman coding costs significantly less than the fixed-length coding. On average, the fixed-length coding costs roughly 1.5x more than the Huffman coding.


- **e.**

If every character has the same frequency, then the tree is going to be balanced. As a result, we can caluclate the cost using tree depth times cost per level. In this situation, cost per level will be n and tree depth will be log(n), giving us an expected cost of nlog(n).
