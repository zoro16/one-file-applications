Both  POSIX threads and OpenMP took almost the same time of calcuation (from 0.028 - 0.032 seconds). 

openMP was very straightforward and easy to implement, just a couple of a lines to finish the job. The only disadvantage I can think of for openMP is that level of control is low comparing to POSIX threads since we do not know what is happening behind the scenes.


POSIX threads or (Pthreads) is a very low-level API for working with threads. Thus, it gives an extrem control over thread management. On the other hand, it can be very complicated to deal with it sometimes, since you have to take care of the syncronization of the parallel parts of the program (Mutex and Semaphores).



### To compile all the files:
    * make
	
	
### To run the files	
	* ./prime-openmp2
	* ./prime-pthread4
	

