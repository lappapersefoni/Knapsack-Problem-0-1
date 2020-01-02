
# Knapsack Solver
This repository contains C++ code of the knapsack 0-1 problem <br/>
The generator folder contains the file knapsack_gen.c and knapsackFilesCreator.c which help us create one knapsack 0-1 problem or a pack of problems<br/>
The problems can solved by using 6 different algorithms: <br/>

- **Greedy approach**<br/>
- **Brute force**<br/>
- **Branch and bound**<br/>
- **Dynamic programming**<br/>
- **Dynamic OR-Tools solver**<br/>
- **Integer OR-Tools solver**<br/>

The solution of each problem is stored in a file<br/>
The solution of pack of problem is stored in a CSV file for generating statistics<br/>

Web Page: (https://lappapersefoni.github.io/knapsack)
## Instructions:
1. Download this repository
2. Run the file Knapsack.exe
3. On the menu select the option 8:Create all knapsack problems (320 files)
   This step will create the folder knapsack_problems that includes 320 knapsack problems files which can be resolved using the Knapsack.exe
4. Select the algorithm with which you want to solve the problems (you can run all algorithms at once or one of them at a time)   
   and create CSV files with the solutions of the problems   

**Knapsack.exe**          This the main solver with many features<br/>
**or_tools_dynamic.exe**  Util that used by the main file to solve a problem using the OR-Tools Dynamic algorithm<br/>
**or_tools_integer.exe**  Util that used by the main file to solve a problem using the OR-Tools Integer algorithm<br/>
**knapsack_gen.exe**      Util that used by the main file to create a knapsack problem<br/>

All of these files has to be to the same folder<br/>

## Other folders:
generator folder: <br/>
    **knapsack_gen.c**      : Contains the code the knapsack generator (C++ code)<br/>
    **knapsackFilesCreator**: This utils calls the knapsack generator to create 320 problems files (C++ code)<br/>
    **oneClickCreator**     : MsDos batch file that call the knapsackFilesCreator (C++ code)<br/>

## Required hardware and software:
CPU: 64bit<br/>
Windows 64bit<br/>
Ram: 4Gb<br/>

## Copyright © Lappa Persefoni 2020<br/>

`January 2020`


