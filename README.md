# AI Powered Power Line Fault Detection
##### October 2019

## Authors : 
* Sudalaiandi Raja Sudalaimuthu
* Jayaraman Revathi
* Jayasri Raghunathan
* Sunil Varghese

Supplying electricity to cities require High to Medium voltage overhead power lines
running for hundreds of miles from the generating stations.These great distances make
it expensive to manually inspect the lines for any damage that doesn't immediately lead
to a power outage.These damages eventually will lead to a power outage or the start of
a fire if not repaired timely. Such kind of damages caused by a tree branch hitting the
line or a flaw in the insulator lead to a phenomenon known as 'partial discharge' - an
electrical discharge which does not bridge the electrodes between an insulation system
completely.

Partial discharges are known as good indicators of degradation of insulation systems.
However the background noise distorts the pattern of partial discharges (PD-pattern)
and decreases the capability of detection methods to recognize the features of PD-pattern
corresponding to the degradation of an insulation system.The objective of the project is
to detect correctly the partial discharge patterns in signals acquired from these power
lines. Creating an effective classifier using this data will make it possible to continuously
monitor power lines for faults and take timely actions.

Resources :  

Dataset :
https://www.kaggle.com/c/vsb-power-line-fault-detection/data

* metadata_train.csv – 8712 x 4
* train.parquet – each signal contains 800k measurements of power line’s voltage

Reference code from the baseline approach :
https://www.kaggle.com/braquino/5-fold-lstm-attention-fully-commented-0-694

IEEE paper  - A complex classification approach of partial discharges from covered conductors in real environment https://ieeexplore.ieee.org/document/7909221

Total execution time : 54 minutes 24 seconds