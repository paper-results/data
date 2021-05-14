## Paper title: Can Higher-Order-Mutants Improve the Performance of Mutation-based Fault Localization?

This folder contain for each benchmark (SIR and Codeflaws) and for each fault the metrics (**Top-N**, **MAP**, and **MTP** ) computed from fault localization accuracy (statement suspiciousness). Each file content on each research questions is presented in the following:

### RQ1:Can HOMs help in improving fault localization accuracy in SFL-Scenario?
* **SIR-SFL-TOP-N.xlsx** is the Top-N of SIR on each program in SFL-Scenario. The result in each table are calculated by different formulas.
* **Codeflaws-SFL-TOP-N.xlsx** is the Top-N of Codeflaws on each program in SFL-Scenario. The result in each table are calculated by different formulas.
* **SIR-SFL-avg-MAP.xlsx** is the average MAP of single-fault programs in SIR. Three formuals are used to compute the MAP.
* **Codeflaws-SFL-avg-MAP.xlsx** is the average MAP of single-fault programs in Codeflaws. Three formuals are used to compute the MAP.

### RQ2:Can HOMs help in improving fault localization accuracy in MFL-Scenario?
* **SIR-MFL-TOP-N.xlsx** is similar to **SIR-SFL-TOP-N.xlsx** but present in multiple-fault programs (from 2-fault to 5-fault) in SIR. 
* **Codeflaws-MFL-TOP-N.xlsx** is similar to **Codeflaws-SFL-TOP-N.xlsx** but present in multiple-fault programs (2-fault and 3-fault) in Codeflaws.
* **SIR-MFL-avg-MAP.xlsx** is similar to **SIR-SFL-avg-MAP.xlsx** but present in multiple-fault programs (from 2-fault to 5-fault) in SIR. 
* **Codeflaws-MFL-avg-MAP.xlsx** is similar to but present in multiple-fault programs (2-fault and 3-fault) in Codeflaws.

### RQ3:Which MBFL formula better for MBFL techniques when doing fault localization?
* **SIR-SFL-TOP-N.xlsx** is same as the file in RQ1.
* **Codeflaws-SFL-TOP-N.xlsx** is same as the file in RQ1.
* **SIR-SFL-avg-MAP.xlsx** is same as the file in RQ1.
* **Codeflaws-SFL-avg-MAP.xlsx** is same as the file in RQ1.
* **SIR-MFL-TOP-N.xlsx** is same as the file in RQ2.
* **Codeflaws-MFL-TOP-N.xlsx** is same as the file in RQ2.
* **SIR-MFL-avg-MAP.xlsx** is same as the file in RQ2.
* **Codeflaws-MFL-avg-MAP.xlsx** is same as the file in RQ2.

### RQ4:What is the execution cost of HOMs when applied to fault localization?
* **MTP.xlsx** is the MTP of different HOMs in SFL-Scenario and MFL-Scenario. For each benchmark, total MTPs are counted by the all versions' MTP.
