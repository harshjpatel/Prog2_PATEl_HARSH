# prog3_PATEL_HARSH

The goal of this assignment is to learn implementing a distributed task execution framework on
Amazon EC2 using SQS. This Assignment will be to implement a task execution framework
CloudKon, run framework on EC2 and use SQS to handle queue of request to load balance across
multiple workers.
We have to make a local worker queue and then it has to run on t2. micro instance with changing
number of threads and then run on it a note the time taken by it. Change no of thread then the
worker gets the tasks according to it and note the throughput and efficiency according to it. That’s
the main task on local machine,
We have to make SQS program which has the client sent the queue to the machine and the worker
het the work tasks according to it. If the worker then implements the work task from Dynamo DB,
if the work tasks is already done there, then it throws them. But if there is no task done like same
ID od task then the worker run it and get the output. The Scheduler is scheduling the process and
the dynamo DB is driven by monitoring System. We have to know how to run this system.
