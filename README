# Ternary-QM
Ternary Quine-McCluskey Logic Optimization

**********************************************
This program is developed by Sung-Yun Lee.
Any question about the program is welcome.
Contact: syun.lee@postech.ac.kr
Web:     http://csdl.postech.ac.kr
**********************************************

## Reference papers
[1]
Title: Ternary Logic Synthesis with Modified Quine-McCluskey Algorithm
Authors: S.-Y.Lee, S.Kim and S.Kang
Conference: IEEE 49th International Symposium on Multiple-Valued Logic (ISMVL), 2019.
[2]
Title: A Logic Synthesis Methodology for Low-Power Ternary Logic Circuits
Authors: S.Kim, S.-Y.Lee, S.Park, K.R.Kim and S.Kang
Journal: IEEE Transactions on Transactions on Circuits and Systems I: Regular Papers (TCAS-I), 2020.

## Execution
==[How to run]========================================================================================================

TQM.exe -input [benchName] -output [outFile] | tee [logFile]

-(Example)------------------------------------------------------------------------------------------------------------

    [benchName] : ./bench/xxx/xxx.txt
    [outFile]   : ./output/xxx/xxx.out
    [logFIle]   : ./log/xxx/xxx.log

    ./TQM.exe -input ./bench/balanced/0_cons.txt -output ./output/balanced/0_cons.out | tee ./log/balanced/0_cons.log
    
      or

    ./TQM.exe -input ./bench/balanced/0_cons.txt -output ./output/balanced/0_cons.out > ./log/balanced/1_cons.log

----------------------------------------------------------------------------------------------------------------------
* [benchName] and [outFile] are necessary!


## Notification
==[Notice]============================================================================================================

You can make new bench with the same format of given bench.
The format is described as follows:

----------------------------------------------------------------------------------------------------------------------

NUM_INPUT X      # Number of input variable
MODE X           # If the ternary logic is balanced, mode becomes 0. If it is unbalanced, mode becomes 1
INPUTi           # Input values of the i-th input variable in truth table
INPUTj           # Input values of the j-th input variable in truth table
...
OUTPUT           # Output values of the truth table

# Etc.
----------------------------------------------------------------------------------------------------------------------
* More information is described in user guide pdf file (UserGuide.pdf)
* You can also download the program at url: http://csdl.postech.ac.kr/downloads/public/TQMSyn.tar.gz
