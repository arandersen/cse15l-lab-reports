# Week 7 Lab Report - Arthur
## Part 1

Task :  TestDocSearch.java, copy the test called testSearchCount, rename the new test to testSearchCount2 and change the query string being tested to tax rather than taxation.

```
Vim TestDocSearch.java  //go to the specific file which in this case is TestDocSearch.java
/testSearchCount        //search the specific method, so by using '/' the following words will be search within the 
                           program
<Enter>                 // it will stop to the specifc word search (testSearchCount), which in this case is the name 
                           of the method
K                       //go to previous line, which means that it goes to one line prior form itself (exp: from 
                           line 10 to line 9)
<Shift> + V             //highight the line, where it highles one whole line from the edge of the screen to the end 
                           of the words in the line
J (x5)                  //selected the highlited line down by 5, continue the highlight and going down to the total 
                           down (J) pressed, this time its 5
Y                       // (yank), copy the file to the clipboard, it will save the highlighted part base on the 
                           previous steps and save in clipboard
J (x6)                  //go below the current method, where it goes down line by line in total 6 times (exp from 
                           line 10 -> line 16)
P                       //paste the copy method from the clipboard, where the highlighted part that is save in the
                           clipboard is paste to the current line
/testSearchCount        //search the specific method, so by using '/' the following words will be search within the 
                           program
<Enter>                 // it will stop to the specifc word search (testSearchCount), which in this case is the name 
                           of the method
W                       // go to the very end of the word, where it moves the cursor from the the beginning to the 
                           end of the word (exp: cursor start at "w" in the contect "We are Great" and after using
                           W it will place the cursor at "t" at the very end)
I                       // go to insert mode, where it change mode to Insert so we can edit and add to the program.
2                       // add "2" as a different method, to differentiate from the first method
<Esc>                   //execute from input to visual mode
:wq                     //save and quit from the program.
<Enter>                 //execute the :wq command save and quit 
```

## Part 2
task 2:    

Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?      

>Personally, I would prefer doing doing it in the vscode, presume that i have the scp command and other commands save in other file. For me doing it in the an IDE environment such as VScode works more conveniently as when i run the bash.sh and if it fails, it will point out the error and lead suggestion to patch up the error. In comparison doing it in terminal its more tedious,especially wehn trying to solve where the problem come from. Also to open one file to another i need to access and go out from one directory to another. While in VScode i can directly open all the file at once in different tab.

   
What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)  

>If there would be a project given, i would definitelty use through vscode, as the flexibility and easy operate makes it more desirable. Especially in a large project, there would be more files and debugging the program, by using vscode it would be more helpful and easier to oeprate.
