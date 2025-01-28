In this problem there was a Java file that's given.
Download the .java file and then open it in VScode.
Once we start running the program we see that we need a password to run this program.
at the end of the program we see that a string is given, so i tired to put it as the password by attaching picoCTF, and the access was denied.
So what i did was i put a print statment to print the buffer after all the for loops as this vault uses all the for loops and i tried it again.
this time access was denied but the buffer value was also printed along with it. So I just took the value and added picoCTF to it and tried to place it in place of the password and it worked.
the flag is :- picoCTF{jU5t_a_sna_3lpm18g947_u_4_m9r54f}
