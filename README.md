# Parallel-Algorithms
A Brief Report on Parallel Algorithms and their Applications

Introduction:
The parallel algorithm is an approach to solve real-world problems as well as
high-level complex data management problems with ease & high efficiency. It
works by dividing a bigger problem into sub smaller problems and then
simultaneously executing the problem on different processors and combining
the data into a final result.
Every day we face many task & challenges which requires high volume if data
processing and by following the regular approach we cannot solve these
tasks or even if some algorithm manages to do so then it will be a big
challenge for the CPU to process and generate the Result.
This is where Parallel algorithm plays its role. These types of algorithms are
carefully designed to manage a large volume of data and then rather than
putting everything onto a single CPU, it divides the problem into subtask that
runs the same algorithm but on a smaller scale with a lesser volume of data
and executes all the subtasks simultaneously on every CPU core. In other
words, multiple processors are used to running the same program with
instructions divided across. Then collect the result and generate the final
result for the task.
As a result, the running time of the program is smaller than the number of
instructions executed.
This report describes the impact of such parallel algorithms on some
problems that are common and useful in our everyday life.


Why and how to improve?
Most parallel algorithms suffer from the issue of Load Balancing. This is the
technique of making sure that each processor is given a similar load of work rather
than the same input size. For example, the task is to find prime numbers in the range
0-200. This task is divided as the processor A is given 0-100 while the processor B is
given 100-200. The input size is the same for both but it is easier to calculate
primality of lower numbers. As a result processor, A will be idle for a time that
processor B is still busy because it has a bigger computational load.
This is why we should improve any parallel algorithm to make sure each processor
carries a similar computational load.
There is a room for improvement when some assumptions are made. Moreover, to
combat the Inherent Sequentiality the program can be split into portions which must
be performed in a sequence and other portion in which order of instruction execution
is not relevant.
A sort of hybrid system can be used in which parallel algorithm behave just like
sequential algorithms where they have to and switch back to parallel whenever
possible. These were some of the ways an improvement can be made.


Conclusions
Parallel Algorithms have a number of applications which are growing. While the idea
is closely linked with parallel computer architecture, there are differences as well.
With the development of parallel algorithms, many sorting algorithms are improved
12
further like the Parallel Merge Sort and the Hyper Quick Sort. We learned that there
can be many other applications of this class of algorithms as well, however, these
require special parallel programming languages which feature data structures such
as hypercubes for communications between the processors.


