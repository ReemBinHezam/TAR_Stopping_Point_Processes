# TAR Stopping Point Processes
Repository for the code of the paper "Stopping Methods for Technology Assisted Reviews based on Point Processes" by Mark Stevenson and Reem Bin-Hezam

## Content
Notebooks for the following:
- [Run Point Processes](https://github.com/ReemBinHezam/TAR_Stopping_Point_Processes/blob/main/run_TAR_stopping_PointProcesses.ipynb)
- [Run Point Processes for Multiple Runs & Visulaization](https://github.com/ReemBinHezam/TAR_Stopping_Point_Processes/blob/main/run_multiple_runs.ipynb)
- [Baselines vs Point Process Across Multiple Datasets Visualization](https://github.com/ReemBinHezam/TAR_Stopping_Point_Processes/blob/main/vis_all_datasets_with_baselines.ipynb)
- [Per Topic Visualization](https://github.com/ReemBinHezam/TAR_Stopping_Point_Processes/blob/main/vis_per_topic.ipynb)
- [T-Test Analysis](https://github.com/ReemBinHezam/TAR_Stopping_Point_Processes/blob/main/run_TTest_IPvsCX.ipynb)

## Data 
Ranking and Relevance files of: 
* CLEF (2017, 2018, 2019)
* TREC (TR , Legal)
* Link to complete datasets ranking inlcuding TREC TR & Legal: [download](https://drive.google.com/file/d/14x2fEPFDmox1_voHtF8QfhmnUyyNnzpP/view?usp=sharing) (~305MB). 
    * add them to *data/rankings* sub-folder
* Links to CLEF qrels for Baselines Comparison: [CLEF (2017, 2018, 2019)](https://github.com/dli1/auto-stop-tar)
   * merge each dataset topics qrels into one file and add them to sub-folder: *data/qrels* 

* Links to CLEF qrels for for Multiple Runs: [CLEF (2017, 2018)](https://github.com/CLEF-TAR/tar)
    * for CLEF2017 , add *qrel_abs_test.txt* to sub-folder: */RunMultipleRankings/CLEFData/clef_runs/2017/relevance* 
    * for CLEF2018 , add *full.test.abs.2018.qrels* to sub-folder: */RunMultipleRankings/CLEFData/clef_runs/2018/relevance*  

* Links to TREC qrels (needs access permission): [TR qrels](https://plg.uwaterloo.ca/~gvcormac/total-recall/2016/qrels/) , [Legal qrels](https://trec.nist.gov/data/legal/10/qrel_leg_int_2010_msg_post.txt). 
    * add them to sub-folder: *data/qrels* 
    * guidlines on how to get access and usage agreements: [TR](https://plg.uwaterloo.ca/~gvcormac/total-recall/2016/guidelines.html) , [Legal](https://trec-legal.umiacs.umd.edu/)

