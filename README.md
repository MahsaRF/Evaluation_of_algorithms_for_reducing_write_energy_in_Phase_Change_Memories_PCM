# Evaluation_of_algorithms_for_reducing_write_energy_in_Phase_Change_Memories_-PCM-

Topic : Evaluation of algorithms for reducing write energy in Phase Change Memories(PCM)
Definition :

One of the most important issue in Main Memories is the potential of scalability, and 
scalability of PCM against DRAM has considerable preference causes PCM has become topic 
issue in scalability and DRAM has proven less attractive from the point of view of scaling. Versus 
this advantage, high energy consumption especially in write operations is inappropriate. In this 
circumstance, Methods based on assessment are proposed and the most of them using 
comparison before writing the data word. In these methods according to proportion of read 
energy consumption to write energy consumption decrease the number of writes in each block 
or word and these methods will not achieve unless by increasing read operations in PCM for 
comparison. One of proposed algorithm operates through manipulation the data. In fact, the 
data word in given address compares with new data word and according to minimizing the 
number of different bits just the differences are manipulated[0]. The other proposed algorithm 
to reduce the energy used in storing a new data block in the Phase-change random access 
memory (PRAM), is to write the same data using fewer bit programming operations. Because 
individual cells in a PRAM can be written independently, we will describe an efficient block 
placement algorithm for choosing a free block whose contents are already similar to a new data 
block ,and updating only data cells whose current values differ from the corresponding bits in a 
write request [0].
Steps :
 In this Course Project we represent two following papers as the main papers.

[1].Data Manipulation Techniques to Reduce Phase Change Memory write energy

[2].Content-Aware Block Placement Algorithm for Reducing PRAM Storage Bit Writes

In addition, the first approach is combination of two above methods that may have better 
result in comparison with two proposed algorithm. One of the biggest challenge in [0] is the 
overhead of extra signature and one problem in [0] is the high latency of comparison. We can 
decrease the overhead of signature used in [0], but by decreasing signature bits ,the probability 
of same signature for different data word is more than signature in [0], so for block that we 
have same signature we can use comparison based on whole data word. This idea can classify 
blocks of PCM and decrease number of comparison of whole data word, on the other hand this 
idea decrease overhead.

References :

[0] http://ieeexplore.ieee.org/xpl/freeabs_all.jsp?arnumber=5907007

[0] http://dl.acm.org/citation.cfm?id=0509009&dl=ACM&coll=DL&CFID=70529969&CFTOKEN=82782009
