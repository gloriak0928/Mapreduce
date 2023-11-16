Project: Mapreduce
===========================


Implement a MapReduce framework in Python inspired by Google’s original MapReduce paper. The framework executes MapReduce programs with distributed processing on a cluster of computers like AWS EMR, Google Dataproc, or Microsoft MapReduce.

The learning goals of this project include MapReduce program execution, basic distributed systems, fault tolerance, OS-provided concurrency facilities (threads and processes), and networking (sockets).

The MapReduce framework consists of two major pieces of code. A Manager listens for user-submitted MapReduce jobs and distributes the work among Workers. Multiple Worker instances receive instructions from the Manager and execute map and reduce tasks that combine to form a MapReduce program.

## Quick start
```console
$ python3 -m venv env/
$ source env/bin/activate
```
