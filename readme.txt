Q.3.27 : Design a file-copying program named filecopy.c using ordinary pipes. This program will be passed two parameters: the name of the file to be copied and the
name of the destination file. The program will then create an ordinary pipe and write the contents of the file to be copied to
the pipe. The child process will read this file from the pipe and write it to the destination file. For example, if we invoke the program as follows:
 ./filecopy input.txt copy.txt 
the file input.txt will be written to the pipe. The child process will read the contents of this file and write it to the destination file copy.txt.
You may write this program using either UNIX or Windows pipes.

Q.4.23 : Write a multithreaded program that outputs prime numbers. This program should work as follows: The user will run the program and will
enter a number on the command line. The program will then create a separate thread that outputs all the prime numbers less than or equal to the number entered by the user

Questions from Silberschatz 10th edition

Solution of 3.27 taken from 
https://github.com/manojkmeena/OS-Project/blob/master/Question%2026%20-%20Design%20a%20file-copying%20program%20named%20filecopy%20using%20ordinary%20pipes.%20This%20program%20will%20be%20passed%20two%20parameters:%20the%20name%20of%20the%20file%20to%20be%20copied%20and%20the%20name%20of%20the%20copied%20file.%20The%20program%20will%20then%20create%20an%20ordinary%20pipe%20and%20write%20the%20contents%20of%20the%20file%20to%20be%20copied%20to%20the%20pipe.%20The%20child%20process%20will%20read%20this%20file%20from%20the%20pipe%20and%20write%20it%20to%20the%20destination%20file.%20For%20example%2C%20if%20we%20invoke%20the%20program%20as%20follows:%20filecopy%20input.txt%20copy.txt%20The%20file%20input.txt%20will%20be%20written%20to%20the%20pipe.%20The%20child%20process%20will%20read%20the%20contents%20of%20this%20file%20and%20write%20it%20to%20the%20destination%20file%20copy.txt.
manojkmeena/OS-Project
with minor modifications
