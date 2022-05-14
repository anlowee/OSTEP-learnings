# Main Content
+ **fork()** system call create a child process which is an exact copy of its parent, the return value in child process is 0.
+ **wait()** system call wait for the children of current process.
+ **exec()** system call execute another program in current process. A successful exec() system call never return, for which the exec() should be a termination of a piece of code and the code after exec() won't be executed.
+ **Signals** are used to control processes, the accessbility of using signals can be managed by dividing different **users**.
+ Only fork(), exec() and wait() can create lots of useful functions. 
