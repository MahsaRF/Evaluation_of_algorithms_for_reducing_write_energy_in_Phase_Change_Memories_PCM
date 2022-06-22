# Evaluation of algorithms for reducing write energy in Phase Change Memories (PCM)

Topic : Evaluation of algorithms for reducing write energy in Phase Change Memories(PCM)

One of the most important issue in Main Memories is the potential of scalability, and 
scalability of PCM against DRAM has considerable preference causes PCM has become topic 
issue in scalability and DRAM has proven less attractive from the point of view of scaling. Versus 
this advantage, high energy consumption especially in write operations is inappropriate. In this 
circumstance, Methods based on assessment are proposed and the most of them using 
comparison before writing the data word. In these methods according to proportion of read 
energy consumption to write energy consumption decrease the number of writes in each block 
or word and these methods will increase read operations in PCM for 
comparison.

We presented some techniques to reduce write energy consumption. These techniques worked based on two important points about 
PCRAM cells. First, independency and addressability in PCRAMs and 
second, free PCM blocks. Based on manipulation content technique which 
writes new data based on last data and number of changes and content aware 
placement technique which writes new data based on free blocks and 
similarity of computed signature of new data and free blocks we presented a 
hybrid method which use two above techniques. In fact, in this method, 
choosing free block for writing new data is not only based on original data, 
but also is dependent to inverse of original data. The results shows that in 
hybrid method we achieved to about %65 overall improvement and about 
%15 improvement against content aware placement technique.
 
In this Project we represent two following papers:

[1] Data Manipulation Techniques to Reduce Phase Change Memory write energy

The general idea in this method is based on reading the stored data before writing the new data. 
According to much more difference between read and write energy consumption has been tried to 
changed cells will been updated. This structure called selective Memory write and proposed based on 
independence of PCM cells. In this method, we read the given cell before writing operation and merely 
which cells that are different with old cells will been updated. Two points in this situation is important. 
First, in the above proposed algorithm we assume swap some write operations with extra read and 
compare operations. But, because the read energy consumption is much less than write energy 
consumption, so extra read operations is not critical in this case. Second, increased latency is not a new 
problem, because the read latency is much less than write latency. For instance, read time is about 
several tens ns but write time is about several hundred ns. 

[2] Content-Aware Block Placement Algorithm for Reducing PRAM Storage Bit Writes

General idea in this method is based on choosing a good free block for minimize the number of 
changes between last stored and new data. The same as last method(XOR masked write) this method 
needs reading some characteristic of stored data before writing new data and this condition needs an 
overhead for each block that called signature. Signature is an overhead for each PCM cell that represent 
that the format of stored data. In fact, if two data have equal signature then those data have 
approximately equal data and the changed is minimized. 
 This methods uses one of important algorithm that called “Data Comparison Write”. DCW is a 
algorithm for optimal writing based on minimizing number of writes.

This project was submitted as part of the Advanced Storage Systems course taught by Professor Hossein Asadi at Sharif University of Technology Fall 2012

[1] https://dl.acm.org/doi/10.1145/1594233.1594290

[2] https://ieeexplore.ieee.org/document/5496996

