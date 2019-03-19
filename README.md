# Liveness-TestCases

## Soot Users
Please, refer to [Soot](https://github.com/ufarooq/Liveness-TestCases/tree/master/Soot) Directory where .txt files Expected output for Liveness Analysis and .png files are relevant CFG. 
***Note: All kind of instructions including if/else (Branches) considered. You can ignore the Constants.***
## LLVM Users
***Note:  Phi Instructions are Considered, and Branch (icmp/br) instructions are NOT considered. Output contains Constants, but it is OPTIONAL to handle.***
### LLVM using in Debug mode
if you have compiled LLVM without using ``` -DCMAKE_BUILD_TYPE=Release``` flags, Please refer to [LLVM Debug](https://github.com/ufarooq/Liveness-TestCases/tree/master/LLVM/debug) Directory where .txt files Expected output for Liveness Analysis and .png files are relevant CFG. 

### LLVM using in Release mode (used -DCMAKE_BUILD_TYPE=Release)
if you have compiled LLVM using ```-DCMAKE_BUILD_TYPE=Release``` flags, Please refer to [LLVM Release](https://github.com/ufarooq/Liveness-TestCases/tree/master/LLVM/release) Directory where .txt files Expected output for Liveness Analysis and .png files are relevant CFG. 
