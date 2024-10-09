# Sky G Fall 2024         

### Oct 9, 2024 Instructions:
I want you to make a script that compares the differences in two bed files:

Something like `bedtools subtract $bed1 $bed2 > diff.bed` then quantifies those comparisons.

Resulting in a table/spreadsheet looking something like this (in an automated fashion):

| bed1_name | bed2_name | bed1_total_length | bed2_total_length | bed1-bed2_length | bed2-bed1_length |
| --------- | --------- | ----------------- | ----------------- | ---------------- | ---------------- |
| name1     | name2     | 150000            | 160000            | 5000             | 25000            |

This allows us to begin to quantify the similarity between bed files.
