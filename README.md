# Chain-Smoker-Problem-
INTRODUCTION:
This project is dedicated to creating a system call that deals with the chain smoker problem. A system call is a request for  a  service  that  is made by the application programs to the operating system; these can be either user system call (without kernel intervention) or  kernel  system  call  (with kernel intervention).

LIMITATIONS AND DEADLOCK HANDLING:
	The key claim of the cigarette smokers problem is that this scenario has no solution for traditional semaphores, as they existed at the time. When this problem was initially proposed, semaphores only provided operations for incrementing or decrementing their internal value by one. The problem proves that, if we are limited to those operations only, there are situations in which avoiding deadlock is provably impossible. Regardless of how the agent and the smoker threads are constructed, once the agent’s structure is fixed, any construction of the smokers will create a possible deadlock situation. 

  We could generalize the cigarette smokers problem to more than three threads. In this generalized form, there would be N smokers and the agent would place only N-1 items on the table. If every thread requires two resources (decrementing two semaphores, acquiring two locks, etc.), then a linear ordering will not prevent deadlock. The total number of available resources must be at least the total number of possible requests that can be made. If there are N threads that can all issue concurrent requests, there must be N instances available for the linear ordering to prevent deadlock.
