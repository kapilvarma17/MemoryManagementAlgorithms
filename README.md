# Memory Management Algorithms
The purpose of this project is to explore the various memory management algorithms for swapping and paging and implement them.
Simulated Algorithms: FIFO, LRU, LFU, MFU, Random Pick

Specifics of the program: 
• Main Memory can hold: 100 MB where page size for 1 page: 1MB = 100 Pages 
• Process sizes can be: 5, 11, 17 and 31 MB (Pages) 
• Each Process has a random amount of CPU Time: 1, 2, 3, 4, 5 seconds. 
• Number of random processes: 150, Sorted on arrival time. 
• A job is taken out from the queue only when there are at least 4 pages available. 
• A process will always start at page 0, then every 100 msec the process references another memory location using the locality of          reference algorithm, this referencing continues till its duration expires.

Results: The Average number of processes that were successfully swapped in are shown below for all the algorithms. 
Random Pick: 1st Run: 1516 2nd Run: 1540 
FCFS:        1st Run: 1499 2nd Run: 1515 
LRU:         1st Run: 1478 2nd Run: 1479 
LFU:         1st Run: 1638 2nd Run: 1621 
MFU:         1st Run: 1566 2nd Run: 1558 

