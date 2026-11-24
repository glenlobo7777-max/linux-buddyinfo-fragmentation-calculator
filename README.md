# linux-buddyinfo-fragmentation-calculator
Excel-based diagnostic tool for analyzing Linux /proc/buddyinfo memory fragmentation.


Linux Buddyinfo Fragmentation Calculator
An Excel-based diagnostic tool for analyzing Linux memory fragmentation using data from /proc/buddyinfo.

Purpose
The calculator helps interpret Linux buddy allocator information and provides fragmentation percentages that can assist with memory and system-performance troubleshooting.

Collecting Input
Run the following command on the Linux system:

cat /proc/buddyinfo
Example:

Node 0, zone DMA
Node 0, zone DMA32
Node 0, zone Normal
Node 1, zone Normal
Copy the appropriate buddyinfo values into the calculator.

What the Calculator Provides
Buddy-order analysis
Free-page information
Memory block-size calculations
Fragmentation percentage by order
Overall fragmentation percentage

Usage
Run cat /proc/buddyinfo.
Identify the node and zone to analyze.
Copy the buddy-order values.
Paste the values into the calculator.
Review the calculated fragmentation levels.

Disclaimer
This project is provided for educational and troubleshooting reference purposes. Validate results against the requirements and behavior of the Linux system being investigated.
