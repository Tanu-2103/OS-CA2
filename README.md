# OS-CA2
Write a program for multilevel queue scheduling algorithm. There must be three
/queues generated. There must be specific range of priority associated with every queue. Now
prompt the user to enter number of processes along with their priority and burst time. Each
process must occupy the respective queue with specific priority range according to its priority.
Apply Round robin algorithm with quantum time 4 on queue with highest priority range. Apply
priority scheduling algorithm on the queue with medium range of priority and First come first
serve algorithm on the queue with lowest range of priority. Each and every queue should get a
quantum time of 10 seconds. Cpu will keep on shifting between queues after every 10
seconds i.e. to apply round robin algorithm of 10 seconds on over all structure.
Calculate Waiting time and turnaround time for every process. The input for number of
processes should be given by the user.

ALGORITHM
    Initiate 3 queues and associate specific range of priority with every queue
    Enter number of processes along with their priority and burst time.
    Each process should occupy respective queue
    Apply Round Robin Algorithm (q=4) with highest priority range
    Apply Priority Scheduling Algorithm on medium priority range
    First Come First Serve on lowest priority range
    Each queue will only get 10 seconds
    Round Robin on overall structure

    q1 : p1,p2,p3  |RR(4)    |
    q2 : p4,p5,p6  |PS    ---| Round Robin (10)
    q3 : p7,p8,p9  |FCFS     |
