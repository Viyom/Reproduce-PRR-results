# Reproduce-PRR-results

#### This repository contains the source code related to the PRR paper submitted to WNS3 2018.

#### Use the following steps to reproduce the result presented in the paper:

##### 1) configure and build the repository using the following commands:
  -  `./waf configure`
  -  `./waf`
    
##### 2) Run the provided shell script with the following command:
  -  `./result.sh`
    
##### 3) The results will be generated and stored in the following files:
 - ClassicResult : Results for SACK based recovery.
 - PrrSSRBResult : Results for PRR recovery with Slow Start Reduction Bound.
 - PrrCRBResult  : Results for PRR recovery with Conservative Reduction Bound.
