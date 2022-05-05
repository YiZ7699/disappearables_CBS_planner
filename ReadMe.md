This is the CBS-based planner code for the disappearables_CHI2022 project (https://github.com/mitmedialab/disappearables_CHI2022). The planner plans toios robot paths on a map that has either one or two stages (one upper stage and one lower stage).

Author: Yi Zheng, Email: yzheng63@usc.edu

**Required Libraries**:

- cmake
- boost library for cpp

If you are using a Linux machine, run the following commands to install the two libraries. 

```
apt-get install build-essential 

apt-get install cmake 
```

**Installation**:

1. Compile and make the code by entering the following command lines in the folder: 

```
cmake .  

make
```

1. Copy the file "planner" to the Control UI folder "ControlUI_v1_x\CBS_planner".
2. The planner will be called when the "PLAN PATHS" button in the control UI is clicked.



