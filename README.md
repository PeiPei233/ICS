# ICS

## Lab6a Checker

1. Download lab6a_checker.exe

2. Drag your `*.exe` or any file excutable by command line to it.

3. If the output is distinguished between the checker and your program, the checker will show you like the following example. `line 2` means the first difference appear in the line 2 of both output. `address 0x57ba` means the different line of instruction shown in LC-3 address. Then the program will save three files in your computer:
   1. `input.txt` the input file
   2. `ans.txt` the output of checker
   3. `output.txt` the output of your program

    Tips: you can copy the instructions in `input.txt` to the LC-3 simulator, assemble it, and see the instructions of the line with difference in the address shown in the checker's message. 

```
Find difference at line 2 (at address 0x57ba):
        Output of checker is 0010000010000100
        Output of main.exe is 0010000000000000
All the data has been saved successfully.
```

Hope that this checker will help you :)
