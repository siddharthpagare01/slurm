# Batch Systems and SLURM MCQs

## Session 1: Batch Systems, Resource Manager, Scheduler

1. **What is a batch system?**
   - A) A system that processes jobs in real-time
   - B) A system that processes jobs in groups
   - C) A system that requires user interaction
   - D) A system that only runs on weekends  
   **Answer:** B

2. **What is the primary function of a resource manager?**
   - A) To manage user accounts
   - B) To allocate resources to jobs
   - C) To monitor network traffic
   - D) To schedule meetings  
   **Answer:** B

3. **Which of the following is a key responsibility of a scheduler?**
   - A) To install software
   - B) To manage hardware failures
   - C) To determine the order of job execution
   - D) To provide user support  
   **Answer:** C

## Session 2 & 3: Submitting and Managing Jobs, Writing the Batch Script

4. **What command is typically used to submit a job in SLURM?**
   - A) `sbatch`
   - B) `srun`
   - C) `squeue`
   - D) `scancel`  
   **Answer:** A

5. **Which of the following is NOT a component of a batch script?**
   - A) Job name
   - B) Resource requests
   - C) User credentials
   - D) Commands to execute  
   **Answer:** C

6. **What is the purpose of the `#SBATCH` directive in a batch script?**
   - A) To define the job name
   - B) To specify resource requirements
   - C) To set environment variables
   - D) All of the above  
   **Answer:** D

## Session 4 & 5: SLURM Installation and Configuration, Submitting and Managing Jobs

7. **Which file is typically used for SLURM configuration?**
   - A) `slurm.conf`
   - B) `batch.conf`
   - C) `scheduler.conf`
   - D) `resource.conf`  
   **Answer:** A

8. **What command would you use to check the status of submitted jobs?**
   - A) `sinfo`
   - B) `squeue`
   - C) `scontrol`
   - D) `sacct`  
   **Answer:** B

9. **In SLURM, what does the `srun` command do?**
   - A) Submits a batch job
   - B) Runs a job interactively
   - C) Cancels a job
   - D) Displays job information  
   **Answer:** B

## Session 6 & 7: Managing Nodes, Setting Server Scheduling Policies

10. **What is the purpose of managing nodes in a cluster?**
    - A) To ensure all nodes are powered on
    - B) To allocate jobs to specific nodes
    - C) To monitor network usage
    - D) To install software updates  
    **Answer:** B

11. **Which scheduling policy allows jobs to be prioritized based on their submission time?**
    - A) Fair share
    - B) FIFO (First In, First Out)
    - C) Backfill
    - D) Priority-based  
    **Answer:** B

12. **What does the term "node" refer to in a computing cluster?**
    - A) A single job
    - B) A single computing unit
    - C) A user account
    - D) A network switch  
    **Answer:** B

## Session 8: Scheduler Algorithm

13. **Which of the following is a common scheduling algorithm used in SLURM?**
    - A) Round Robin
    - B) Shortest Job First
    - C) Backfill
    - D) All of the above  
    **Answer:** D

14. **What is the main goal of a scheduling algorithm?**
    - A) To maximize resource utilization
    - B) To minimize job wait time
    - C) To ensure fairness among users
    - D) All of the above  
    **Answer:** D

## Session 9 & 10: SLURM Accounting

15. **What is SLURM accounting used for?**
    - A) To track resource usage
    - B) To manage user permissions
    - C) To configure nodes
    - D) To install software  
   **Answer:** A

16. **Which command can be used to view accounting information in SLURM?**
    - A) `sacct`
    - B) `sinfo`
    - C) `squeue`
    - D) `scontrol`  
   **Answer:** A

17. **What type of information can SLURM accounting provide?**
    - A) Job completion times
    - B) Resource usage statistics
    - C) User job history
    - D) All of the above  
   **Answer:** D

18. **In SLURM, what does the `sacct` command do?**
    - A) Submits a job
    - B) Displays job accounting information
    - C) Cancels a job
    - D) Shows the status of nodes  
   **Answer:** B

19. **Which of the following is a benefit of using SLURM accounting?**
    - A) Improved job scheduling
    - B) Enhanced resource allocation
    - C) Detailed usage reports for users
    - D) All of the above  
   **Answer:** D

20. **What is the default location for SLURM accounting logs?**
    - A) `/var/log/slurm`
    - B) `/var/lib/slurm`
    - C) `/etc/slurm`
    - D) `/usr/local/slurm`  
   **Answer:** B

## Conclusion

This is a sample of 20 MCQs based on the provided lecture topics. You can continue to create additional questions following this format to reach the desired total of 200 questions. ```markdown
## Additional MCQs

21. **What command is used to cancel a job in SLURM?**
    - A) `scancel`
    - B) `scontrol`
    - C) `squeue`
    - D) `sinfo`  
   **Answer:** A

22. **Which SLURM command provides information about the state of the nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

23. **What does the `--ntasks` option specify in a SLURM job submission?**
    - A) The number of nodes to use
    - B) The number of tasks to run
    - C) The amount of memory required
    - D) The job priority  
   **Answer:** B

24. **In SLURM, what is the purpose of the `--time` option?**
    - A) To set the maximum runtime for a job
    - B) To specify the time of day to run a job
    - C) To define the time zone for the job
    - D) To schedule recurring jobs  
   **Answer:** A

25. **Which of the following is a valid job state in SLURM?**
    - A) RUNNING
    - B) PENDING
    - C) COMPLETED
    - D) All of the above  
   **Answer:** D

26. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

27. **Which SLURM command would you use to view detailed information about a specific job?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol show job`
    - D) `sacct`  
   **Answer:** C

28. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

29. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

30. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

31. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

32. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

33. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

34. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

35. **Which of the following is a valid SLURM job dependency type?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

36. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

37. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

38. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

39. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

40. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

41. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

42. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

43. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

44. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

45. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

46. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

47. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

48. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

49. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

50. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

51. **What does the `-- ```markdown
mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

52. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

53. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

54. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

55. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

56. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

57. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

58. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

59. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

60. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

61. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

62. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

63. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

64. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

65. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

66. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

67. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

68. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

69. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

70. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

71. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

72. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

73. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

74. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

75. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

76. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

77. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

78. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

79. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

80. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

81. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

82. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

83. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

84. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

85. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

86. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

87. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

88. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

89. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

90. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

91. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

92. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

93. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

94. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

95. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

96. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

97. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

98. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

99. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

100. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

101. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

102. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

103. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

104. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

105. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

106. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

107. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

108. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

109. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

110. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job 's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

111. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

112. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

113. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

114. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

115. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

116. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

117. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

118. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

119. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

120. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

121. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

122. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

123. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

124. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

125. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

126. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

127. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

128. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

129. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

130. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

131. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

132. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

133. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

134. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

135. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

136. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

137. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

138. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

139. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A 140. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

141. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

142. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

143. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

144. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

145. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

146. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

147. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

148. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

149. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

150. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

151. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

152. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

153. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

154. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

155. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

156. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

157. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

158. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

159. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

160. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

161. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

162. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

163. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

164. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

165. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

166. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

167. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

168. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

169. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D - A) A scheduling policy for interactive jobs  
   **Answer:** A

170. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

171. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

172. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

173. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

174. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

175. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

176. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

177. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

178. **What does the `--exclude` option do in a SLURM job submission?**
    - A) Excludes specific nodes from being used for the job
    - B) Excludes certain jobs from the queue
    - C) Excludes specific users from submitting jobs
    - D) Excludes certain resources from being allocated  
   **Answer:** A

179. **In SLURM, what is the purpose of the `--job-name` option?**
    - A) To specify the name of the job for identification
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the output file name  
   **Answer:** A

180. **Which of the following commands is used to view the details of a specific node in SLURM?**
    - A) `sinfo`
    - B) `scontrol show node`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** B

181. **What does the `--cpus-per-task` option specify in a SLURM job submission?**
    - A) The total number of CPUs required for the job
    - B) The number of CPUs allocated for each task
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

182. **In SLURM, what is the purpose of the `--output` option?**
    - A) To specify the output file for job logs
    - B) To define the job's resource limits
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** A

183. **Which command would you use to view the history of completed jobs in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `sacct`
    - D) `scontrol`  
   **Answer:** C

184. **What does the `--time` option specify in a SLURM job submission?**
    - A) The maximum runtime for the job
    - B) The time of day to run the job
    - C) The time zone for the job
    - D) The duration of the job's execution  
   **Answer:** A

185. **In SLURM, what is the purpose of the `--nice` option?**
    - A) To set the job's priority level
    - B) To define the job's resource limits
    - C) To specify the output file name
    - D) To set the maximum runtime for the job  
   **Answer:** A

186. **Which of the following is a valid SLURM job state?**
    - A) RUNNING
    - B) PENDING
    - C) FAILED
    - D) All of the above  
   **Answer:** D

187. **What is the function of the `scontrol` command in SLURM?**
    - A) To submit jobs
    - B) To control job execution and manage SLURM configuration
    - C) To display job status
    - D) To cancel jobs  
   **Answer:** B

188. **Which SLURM command would you use to view the list of available nodes?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

189. **What does the `--mem` option specify in a SLURM job submission?**
    - A) The number of CPUs required
    - B) The amount of memory required for the job
    - C) The maximum runtime for the job
    - D) The job priority  
   **Answer:** B

190. **Which of the following is a common resource request in a SLURM batch script?**
    - A) `#SBATCH --cpus-per-task=4`
    - B) `#SBATCH --job-name=myjob`
    - C) `#SBATCH --output=result.txt`
    - D) All of the above  
   **Answer:** D

191. **What is the purpose of the `--partition` option in SLURM?**
    - A) To specify the job priority
    - B) To define the job's resource limits
    - C) To select a specific queue for job submission
    - D) To set the job's runtime  
   **Answer:** C

192. **In SLURM, what does the term "backfill" refer to?**
    - A) A method to fill idle resources with smaller jobs
    - B) A way to prioritize long-running jobs
    - C) A technique to manage node failures
    - D) A scheduling policy for interactive jobs  
   **Answer:** A

193. **What is the default scheduling policy in SLURM?**
    - A) FIFO
    - B) Fair share
    - C) Backfill
    - D) Priority-based  
   **Answer:** A

194. **Which command would you use to view the list of available partitions in SLURM?**
    - A) `sinfo`
    - B) `squeue`
    - C) `scontrol`
    - D) `sacct`  
   **Answer:** A

195. **What does the `--gres` option specify in a SLURM job submission?**
    - A) General resource requests, such as GPUs
    - B) The maximum runtime for the job
    - C) The number of nodes required
    - D) The job priority  
   **Answer:** A

196. **Which of the following is a valid job dependency type in SLURM?**
    - A) `after`
    - B) `afterok`
    - C) `afternotok`
    - D) All of the above  
   **Answer:** D

197. **What is the purpose of the `--array` option in SLURM?**
    - A) To submit multiple jobs
    - B) To create a job array for parameter sweeps
    - C) To specify job dependencies
    - D) To define resource limits  
   **Answer:** B

198. **In SLURM, what does the `squeue` command display?**
    - A) The status of nodes
    - B) The list of submitted jobs
    - C) The configuration of SLURM
    - D) The accounting information  
   **Answer:** B

199. **What is the purpose of the `--mail-type` option in a SLURM job submission?**
    - A) To specify the email address for notifications
    - B) To define the type of email notifications to receive
    - C) To set the job's priority
    - D) To specify the job's runtime  
   **Answer:** B

200. **Which command is used to view the configuration of SLURM?**
    - A) `scontrol show config`
    - B) `sinfo`
    - C) `squeue`
    - D) `sacct`  
   **Answer:** A

## Conclusion

This completes the set of 200 multiple-choice questions (MCQs) based on the provided lecture topics related to batch systems and SLURM. You can use this format to create additional questions or modify existing ones as needed.
