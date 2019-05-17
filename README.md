# Recruit Reference Program

This is a tool that can recruit genes as representation for the original dataset

=========================  RRP  ==========================
               Recruit Refernece Program
                         V1.1.0
     Contact: Kenneth Shang <kenneth.shang@foxmail.com>
----------------------------------------------------------


========================  USAGE  =========================
   
  python3 recruit_ref.py [options] -n <reference number> -s <strides> -l <length>
   
======================== PARAMETERS ==========================
   
  -h   print out usage information
  -n   total number of reference you want to recruit from the dataset 
  -s   strides for creating reads from the dataset
  -l   length of the reads that you want to use to creat reads from the dataset
  -t   number of threads that you want to use
   
======================== EXAMPLE =========================
   
  python3 recruit_ref.py -n 10 -s 10 -l 100
