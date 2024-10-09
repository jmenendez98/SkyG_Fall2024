# Sky G Fall 2024         

## Time Logging Expectations:    
ALL TIME worked must be logged in this [google sheet](https://docs.google.com/spreadsheets/d/1IkYb6XFlZMOGz5Go2r0pR5Kfzz5ZsBFbf5xhQ5cPZeY/edit?usp=sharing).     

Here you are expected to fill out      
1. the date      
2. the time range worked    
3. location    
4. what you worked on, please be detailed!    

### Oct 9, 2024 Instructions:

**I want you to make a script that compares the differences in two bed files**

1. First step is to create a function to calculate the length of a bed file.    

2. Then find the differences in those bedfiles. Something like `bedtools subtract -a $bed1 -b $bed2 > diff.bed`.      

3. Automatically create a spreadsheet like below:      

| bed1_name | bed2_name | bed1_total_length | bed2_total_length | bed1-bed2_length | bed2-bed1_length |
| --------- | --------- | ----------------- | ----------------- | ---------------- | ---------------- |
| name1     | name2     | 150000            | 160000            | 5000             | 25000            |


#### **Please start with the chrX duplex subset in the `data` folder of this repository.**
