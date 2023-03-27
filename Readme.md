---
title: "ILLINI Datathon 2023"
author: "Wenqi Zeng, Xiangxuan Yu, Jiayi Pan, Jiayi Pan"
date: "2023-03-26"
output: html_document
---

Model forecasting for number of monthly charge offs

Members

   *  Wenqi Zeng <wenqiz4@illinois.edu>
   * Xiangxuan Yu <xy40@illinois.edu>
   * Jiayi Pan <jiayip3@illinois.edu>
   * Frank Sun <fengshi2@illinois.edu>

All copyright reserved by Apical_4

### Description

The purpose of this project is to do model forecasting for accurate number of monthly chargeoffs from 2020/02 to 2021/01 for Synchrony. The training dataset is the customers' data related to chargeoffs, and the tool we use is fb prophet forecasting with macroeconomic data as predictors.

### File Structures
* **Training_data**: Includes all training data that are characteristics that related to charge offs
* **Macro_data**: Includes data from 2000/01 to 2035/12 for different macroeconomic variables
* **Forecast_starting_data**: Includes data all training data that are characteristics that related to charge offs in 2020/01 

### Acknowledgement
We would like to acknowledge all sponsors for sponsoring the ILLINI Datathon 2023. We would also like to thank the University of Illinois Statistics Department for hosting the event.

### Youtube Video Link

<https://youtu.be/PBqkn9pFYEo>

### Model output 

   * Month  Accounts_charged_off 
   * 202002    1001.276 
   * 202003   591.3728
   * 202004   671.778
   * 202005   793.5513
   * 202006   1040.4959
   * 202007   867.6146
   * 202008   893.6631
   * 202009   923.944
   * 202010   947.4532
   * 202011   898.8165
   * 202012   534.8054
   * 202101   1645.1536
