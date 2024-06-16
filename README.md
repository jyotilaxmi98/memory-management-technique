# memory-management-technique
<p> The program performs a comparative study between a paging system and a non-paging system. It also analyzes the performance of the paging system based on various parameters such as page-replacement algorithms (LRU, FIFO, Random), swap-space size, and page size. The program is divided into three submodules:

1.Data Generator <br>
2.Non-Paging System <br>
3.Paging System <br>

<b>Submodules</b> <br>

1.Data Generator

<li>Simulates data generation for testing memory allocation.</li>
<li>Produces a sequence of memory access requests and job sizes to simulate real-world scenarios.<br>
  
2.Non-Paging System</li>

<li>Implements contiguous allocation using the First Fit algorithm.</li>
<li>First Fit Algorithm:</li>
  <li>Searches for the first available memory block large enough to accommodate the job.</li>
  <li>Allocates memory contiguously, which can lead to fragmentation.</li>
<li>Objective: To analyze how efficiently memory is utilized and the system's performance with varying job sizes and memory demands.<br>
  
3.Paging System

<li>Implements memory allocation using paging, dividing memory into fixed-sized pages.</li>
<li>Page-Replacement Algorithms:</li>
<li>LRU (Least Recently Used): Replaces the page that has not been used for the longest period.</li>
FIFO (First-In-First-Out): Replaces the oldest page in memory.
Random: Replaces a randomly chosen page.
Parameters Analyzed:
Page-Replacement Algorithms: Evaluates the impact of different algorithms on system performance.
Swap-Space Size: Analyzes how varying the swap-space size affects performance.
Page Size: Investigates the effect of different page sizes on memory management efficiency.
Comparative Analysis
Memory Utilization: Comparison of how efficiently memory is used in both systems.
Performance Metrics: Evaluates metrics such as execution time, page faults, and fragmentation.
Impact of Parameters: Assesses how the page-replacement algorithm, swap-space size, and page size influence the performance of the paging system.
This structured approach allows a comprehensive comparison of the two memory management techniques and provides insights into optimizing the paging system's performance.





</p>
