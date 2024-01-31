# Day 1

## Work assigned

- Tool flow of Vitis and Vivado
- Printing Hello World

## Work Completed

### Steps to follow are:-

- Step 1:- Open ternimal and enter the path listed in first.sh which is in Home/Gaurav/Work directory , and then start vitis
- Step 2:- select the hardware file (XSA) by selecting zcu102 , Next
- Step 3:- Give the project name , Next
- Step 3:- Select the Hello World program and click on Finish the tool will then load the program
- Step 4:- Once the program is loaded , Build the entire program.
- Step 5:- After building the program , run the Debug as -> Run as Hardware where the code will be dumped on the board and hence the output will be seen on either CuteCom or Vitis Terminal (only one out of both will show the output).
- In order to see the output we have to try to see what USB port the board is responding.
- For vitis terminal we first had to run
  ''' bash
  sudo chmod 666 /dev/ttyUSB0
  sudo chmod 666 /dev/ttyUSB1
  sudo chmod 666 /dev/ttyUSB2
  sudo chmod 666 /dev/ttyUSB3
  '''
  The above command are to be run on terminal. This is used to activate the ports for vitis terminal but for CuteCom the ports are always listening just have to connect to the right

## Work pending

- We had to complete the Hello world exercise because of FSBL error

- For vitis terminal we first had to run

```bash
    sudo chmod 666 /dev/ttyUSB0
    sudo chmod 666 /dev/ttyUSB1
    sudo chmod 666 /dev/ttyUSB2
    sudo chmod 666 /dev/ttyUSB3
```

The above command are to be run on terminal. This is used to activate the ports for vitis terminal but for CuteCom the ports are always listening just have to connect to the right

### The videos we referred :-

- [Hello world video using Xilinx Zynq, Vivado 2020, and Vitis](https://www.youtube.com/watch?v=Mb-cStd4Tqs)
- [Xillinx Vitis Introduction| Hello World with Vitis](https://www.youtube.com/watch?v=LU9hP7KLDgE&t=452s)
- [FSBL Creation and Source Debug in Xilinx Vitis 2019.2](https://www.css-techhelp.com/post/fsbl-creation-and-source-debug-in-xilinx-vitis-2019-2)

# Day 2

## Work assigned

- Tool flow of Vitis and Vivado
- Complete Hello World

## Work Completed

- Completed the Hello World Excercise
- Learnt about FSBL , .xsa , build and debug parameters

### Materials used 
- [ZCU102 Evaluation Board](https://www.xilinx.com/support/documents/boards_and_kits/zcu102/ug1182-zcu102-eval-bd.pdf)
- Detailed understanding on processors is in folder [Processors](https://github.com/ISRO-Project/Shashank/blob/main/Processors)


# Day 3

## Worked assigned
- Connect the CuteCom to the board and print hello world instead of vitis terminal 
- Do some operation on GPIO 
- Interactive mode , that is take user input and print result accordingly 
- Write basic VHDL code and change the output on GPIO with respect to commands 

## worked complete 
- Connected the CuteCom 
- We tried to do the GPIO operation but we dont have the bsp file for the zcu102 which is the board support package for zcu102.


## Work pending 
- Download the bsp for zcu102 and complete the gpio task