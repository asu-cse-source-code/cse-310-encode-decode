# Encode/Decode Program for CSE 310 @ ASU
This is a program that will take std::in input and output to std::out. However both can be redirected from/to txt files. Pretty fun program to build overall.

## How To Run
* Clone the repository onto your machine
* Create txt file to encode/decode or use some that I already have in the repository
* Move the txt file you want to use into the Code folder
* cd into the Code folder
```bash
# In terminal
cd Code/
```
* Build your executables for encode and decode
```bash
# In terminal
make encode
make decode
```
* Run commands to encode and decode your txt file
```bash
# In terminal
# Encode with insertion sort
./encode insertion < your-txt-file.txt > encoded-your-txt-file.txt
# OR with quick sort
./encode quick < your-txt-file.txt > encoded-your-txt-file.txt

# Decode with insertion sort
./decode insertion < encoded-your-txt-file.txt > decoded-your-txt-file.txt
# OR with quick sort
./decode quick < encoded-your-txt-file.txt > decoded-your-txt-file.txt
```
* Test to see the decode worked
```bash
# In terminal
diff decoded-your-txt-file.txt your-txt-file.txt
```