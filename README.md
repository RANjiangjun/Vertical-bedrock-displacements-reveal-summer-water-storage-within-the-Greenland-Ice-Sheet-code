
# Last update 2023.11.28

## 1. Introduction
This repository contains the core script for estimating the summer water storage from GNSS data.
The sample code is written in MATLAB. With the following file structure, you can run the demo directly.


## 2. File Structure
Input:  .mat files for GNSS data
Src
    --/inversion_Reg0E2013.m                                   : Main script to estimate the summer water storage.
    --/est_Thet_Bet_y1Er_Reg0Eanyy_Reg0B_Reg0ErMean_E_r_pavel.m: Function used in inversion_Reg0E2013.m.
	  --/selected_time_series_to_given_time_interval.m           : Function used in inversion_Reg0E2013.m.
Output: Path to store the output.						 

## Corresponding authors
If you have any question about the codes , please contact Jiangjun RAN (ranjj@sustech.edu.cn).

