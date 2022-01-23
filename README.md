# Crypto Arbitrage
A financial analysis to determine if any arbitrage opportunities exist between two exchanges: Bitstamp and Coinbase from its 1st Quarter 2018 historical dataframes. Three aspects to financial analysis are:
  1. Collect data: Collect CSV data in a Jupyter notebook file.
  2. Prepare the datasets for analysis by cleaning missing and erroneous data.
  3. Analyze the data through summary statistics and visualizations, and using information to select areas for a deeper analysis to identify arbitrage opportunities. 

---

## Technologies

This project uses the following libraries and dependencies:
+ Anaconda: an open source package and environment management system.
+ JupyterLab: an extensive environment using web-based user interface designed for data analysis. 
+ Pandas: (included in Anaconda) a Python package data analysis toolkit.
+ Pathlib: imports modules.
+ matplotlib inline: library to create static, animated, and interactive visualizations in JupyterLab.

---

## Installation Guide

Check to ensure that Jupyterlab is installed on your machine by entering the following into your environment:
```
pip install jupyterlab
```
To launch JupyterLab:
  1. Open terminal window, and type ```conda activate dev```.
  2. Type ```jupyter lab```. JupyterLab user interface should open in your browser. 
      a. Or copy and paste one of the URLs: "http://localhost:8888/lab?token=..." into web browser. 

To exit JupyterLab:
  1. On your web browser, use the Run button to shut down any running kernel sessions.
  2. On the menu bar, on the File menu, select Shut Down. 
  3. Okay to close tabs once a dialog box with "Server stopped" message indicates the server has stopped. 
  4. Navigate to terminal window, where you launched JupyterLab and type ```conda deactivate```. This will return you to your ```base``` environment. 

---
## Usage 

Using the technologies to import CSV files, create dataframes, and clean up data:  
![image](https://user-images.githubusercontent.com/96001018/150673359-29ef544d-517c-4305-bdbd-8fb4af73445c.png)

We can create and overlay graphs to visualize how the two exchanges performed during 1st Qtr 2018:
![image](https://user-images.githubusercontent.com/96001018/150673618-4087b2c2-3a79-4ff1-b7eb-9563ebf8f1e2.png)

Three dates in each time period (early, middle, and late) were selected to identify arbitrage opportunities. Summary statistics are generated to describe parameters, e.g. if each date spread returns are greater than 1%.   
![image](https://user-images.githubusercontent.com/96001018/150674079-2be88fbb-1aa2-4183-af52-7100e2241496.png)

Different functions and tools within the application help calculate and plot data. It's key when identifying any patterns or trends in the profits across the three time periods. 

## Contributors

Leigh Anne Badua leighbadua@gmail.com 

---

## License

+ [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)
