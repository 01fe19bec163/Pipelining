# Pipelining
Pipelining is a process of accumulating instructions from the processor through a pipeline.
It allows storing and executing instructions in an orderly process.
Through pipeling, multiple instructions are executed simultaneously which increases the throughput of the instructions.
An example of pipelinig is considered with the following stage wise operations :
stage-1 : Read two 16-bit numbers from the specified registers and store them in A and B.
  stage-2 : Perform an ALU operation on A and B specified by some function and store it in Z.
  stage-3 : Write the value of Z in the some register.
  stage-4 : Also write the value of Z in specified memory location.
 For the consecutive pipeline stages, non-overlapping two phase clocks are used.

