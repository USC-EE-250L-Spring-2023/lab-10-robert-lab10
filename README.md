# Lab 10
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- team member 1: Jiansong Li
- team member 2: Robert Zhang

## Lab Question Answers

Question 1: If it want to be worthwhile to offload processing tasks, the PC has more processing power than the current device which is performing the task. Otherwise, if the task requires excessive and unhandable computation, the device experience performance issue and not able to complete the task on time, or the task require analysis or processing that are not avaiable, it will better to offload processing tasks. Then, it will be not worthwhile when the task is really simple and not require excessive processing power, the device can handle the task without any issues, or the task involves some datat that are not transferable to other device for some reasons.

Question 2:  We need to join the thread because we need ensure that the main thread waits for the offloaded thread to finish ongoing executed task before running with other tasks. If we do not join the thread here, the main thread might exit before the offloaded thread complete its task.      ----Reference from Chat GPT

Question 3: The functions are executing concurrently because both offload_process1 and process2 functions are running at the same time. Offload_process1 function is executed in a separate thread while the process2 is executed in the main thread.  The difference between parallel execution and concurrent execution is that parallel execution allow multiple tasks running simultaneously. Parallel execution requires hardware support and is always used for intensive task that can be broken down into subtasks.  

Question 4: The best offloading mode is process1 because the mean execution time is the lowest which means that it allows users to finish the task in shortest amount of time.  

Question 5: The worst offloading mode is None since it takes highest amount of time to execute all the tasks. 

Question 6: In real-world applicatuion, processing functions which require computationally intensive or a lot of resources are more likely to be used. If you want to conduct tasks related to image or video processing, machine learning, language process, or other intensive tasks, they are good examples for offloading to a server.  For the second part of the question, when I aimed to achieve a reduced load on local hardware, access to specific hardware, or want to scale up or down the processing demand, I would want to offload these functions to a server.
