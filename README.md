# Coroutines

## Lesson-1
 - function and thread
   - function is a sequence of instructions which need to execute
   - it takes input and gives output
   ````
    fun myFun(input:type):returnType{
   sequence of insturctions
   return Type
    }
   ````
    - A thread describes in which context this sequence of instructions should be executed
 - why is threading important for android apps?
   - In any app all insturctiuion executed on a single thread called Main thread
      which is ok for ui changes but coming to network calls and DB intractions 
      it is not optimal leads to frame drops and performances issues
   - Here we use Multithreading,we assign heavy to other thread instead of main thread
 
## coroutines vs threads
   - coroutines 
     - executed within a thread
     - coroutines are suspendable
     - they can switch their context
   - coroutines are lightweight threads with some useful extra functionality
      

      
