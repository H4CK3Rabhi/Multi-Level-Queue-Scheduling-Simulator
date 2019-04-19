# Multi-Level-Queue-Scheduling-Simulator

The task is to Implement a multilevel Queue Simulator with 2 Queues:

### Queue 1: SRTF(Shortest Remaning Time First):
This is the Queue of Highest Priority Which Schedules Processes using SRTF approach which is a greedy Approach whereby we pre-empt a process if the next process in readyQueue has the remaining execution time which is less than the running one.
This with Absolute certainity give the lowest possible Average Waiting Time(Thus can also be Used for benchmarking other Algorithms)

### Queue 2: RR(Round Robin Scheduling Algorithm):
This is the Queue of Lower Priority then Queue 1 and Schedules Processes using Round Robin Approach which Assigns a fixed Time Quantum/Time Slice to Each Process in ready Queue to Execute and When that time slice expires and process has not completed its execution then it is placed at the End of Queue

### Queue Management Policy
If The No Process is there in higher priority Queue then only the lower priority Queue gets a chance to Execute and the instant new Process arrives in Higher Priority Queue the Lower Priority Queue process is terminated

