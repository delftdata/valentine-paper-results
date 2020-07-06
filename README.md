# valentine-paper-results

In this repository is showcased the output of the [Valentine Experiment Suite](https://github.com/delftdata/valentine-suite). 

The [output](https://github.com/delftdata/valentine-paper-results/tree/master/output) 
folder contains the zip files with the suite's output per method. 

The [Jupyter notebook](https://github.com/delftdata/valentine-paper-results/blob/master/Visualization-Final.ipynb)
 contains the code used for producing all the visualizations that accompany the paper. 
 The visualizations can be found in the [plots](https://github.com/delftdata/valentine-paper-results/tree/master/plots) folder.

#### Instructions
* Create a virtual environment

    `virtualenv valentine`
* Install the python packages

    `pip install -r requirements.txt`
* Unzip all the folders from the [output](https://github.com/delftdata/valentine-paper-results/tree/master/output) 
and place the folders in a new one called _data_
* Run the jupyter notebook and update the path to the data folder (Step 0 in the notebook)
* Run each cell one by one until the end, where the plots are generated and saved automatically in the 
[plots](https://github.com/delftdata/valentine-paper-results/tree/master/plots) folder.