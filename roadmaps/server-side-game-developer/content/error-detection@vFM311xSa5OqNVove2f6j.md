# Error Detection

TCP detects transmission errors using its mandatory checksum field, which covers the segment header and data. Corrupted segments are silently discarded, triggering retransmission through the normal acknowledgment and timeout mechanism.

Visit the following resources to learn more:

- [@article@Checksum - Wikipedia](https://en.wikipedia.org/wiki/Checksum)
- [@article@What is Error Detection? - IBM](https://www.ibm.com/think/topics/error-detection)
- [@article@Cyclic Redundancy Check - Wikipedia](https://en.wikipedia.org/wiki/Cyclic_redundancy_check)
- [@article@Detecting and Correcting Bit Errors - Princeton University](https://www.cs.princeton.edu/courses/archive/spring19/cos463/lectures/L08-error-control.pdf)