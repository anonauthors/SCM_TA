# SCM_TA: How to run the implemented code
The experiment is divided into several parts where each part is included in a different branch (the default branch provides the implementation of the greedy local search NSGA-II).

The only thing is needed to run the code is cloning the appropriate *branch* in a machine with following requirements provided:<br/>

1. having a JVM through installing jre or jdk >= 1.8.0 on your underlying machine.
2. A minimum of 6 GB RAM and cpu > Corei5

In order to run the experiments, please go through following steps:

I. You could try to run the code from the terminal (CMD in windows) or using an IDE (we suggest *eclipse* in this regard since there are code dependencies (to jgrahpt and MOEAFramework) that is better to be handeld by an IDE).<br/>
II. You just need to compile the provided code in SCM_TA-V1 package (in src dir), and then run the **Assignment** class which contains the main method. Once the code gets run, the application asks for the name of project (JDT or Platform), file number (one of the snapshots) and, etc. <br/>
III. In the end, results will be located in the appropriate dirs (which is the *result* folder).
