# IKHRC-Data-Fusion
Fusion data from multiple csv to one csv

Data are collected from remote broker through a metatrader 4 expert advisor.
https://github.com/reuniware/Metatrader4-Ichimoku-KumoBreakOut/blob/master/IchimokuExpertM15_RealtimeDataSniffer.mq4

Then all the files created can be fusionned thanks to this C# app (IKHRC Data Fusion) into multiple files of 20Megabytes each (250000 lines of data).

You can easily adapt the source code for fusionning into one single output csv file, or split the multiple output files to less or more lines of data.

