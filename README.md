# lab12

The lab description is about implementing the threads functionalities and also synchronization among threads. 

I have used the program that has been given in the assingment and upgraded it to meet the requirements for the lab12. 

1) Initiallly i have craeted the a structure that store the details of the thread and also sum of elements of the array that has been created from the number provided by the user. 
2) Than in the main funciton i have craeted a array of structure to store the values of each theird that has been created during the program execution. 
3) The number of threads will be taken from command line arguments. 
4) According to the number given in the commmand line arguements we create an array from 1 to that number.
5) By using the pthread_create function i have called the compute function by passing the structure for every "i" where i is less than size of the thread. 
6) for every ireration i have sent the updated structure as a variable to compute funciton.
7) Using the muthex function the sum value is updated, the mutex function allows synchronization. 
8) finally using the for loop i have counted the sum of the thread by using sturture variable 
9) and printed the sum on the output teminal.   
