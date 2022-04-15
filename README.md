# Matrix Profile

This repository contains project outcomes conducted by David Chen, [Taemin Heo](http://taeminheo.com), and [Dr. Lance Manuel](https://lancemanuel.netlify.app/) during Spring 2021 at the University of Texas at Austin.
We explored trends and anomalies in ocean data.
For the exploration, we studied Matrix Profile which identifies motifs (a repeated pattern in a time series) and discords (an anomaly).

## Hadley Centre Central England Temperature (HadCET) Dataset Demo
[HadCET_Demo.ipynb](HadCET_Demo.ipynb) summarizes our analysis on the [HadCET dataset](https://www.metoffice.gov.uk/hadobs/hadcet/). We organized the dataset and setup [stumpy](https://stumpy.readthedocs.io/en/latest/Tutorial_STUMPY_Basics.html) for analyzing Motifs and Anomalies of HadCET. 

 ![HadCET_Demo_Motif](/images/HadCET_Demo_Motif.png)
 
 ![HadCET_Demo_Discord](/images/HadCET_Demo_Discord.png)
 
## National Data Buoy Center (NDBC) Dataset Demo
[NDBC_Demo.ipynb](NDBC_Demo.ipynb) summarizes our analysis on the [NDBC dataset](https://www.ndbc.noaa.gov/). We retrieved the dataset and setup [stumpy](https://stumpy.readthedocs.io/en/latest/Tutorial_STUMPY_Basics.html) for analyzing Motifs and Anomalies of ocean wave stiffness. 

 ![OceanWaveStiffness_Demo_Motif](/images/NDBC_Demo_Motif.png)
 
 ![OceanWaveStiffness_Demo_Discord](/images/NDBC_Demo_Discord.png)
 
## Scotland Metocean dataset Demo - Testing Different Window Size 
[Scotland_WindowSize.ipynb](NDBC_Demo.ipynb) summarizes our analysis on the [Scotland Metocean dataset](https://ieeexplore.ieee.org/abstract/document/9389310). For this demo, we tested how different lengths of windows affect to the detected Motifs of significant wave height and wind speed.


## Reference Links
### Matrix Profile
https://towardsdatascience.com/introduction-to-matrix-profiles-5568f3375d90   
https://matrixprofile.org/   
https://matrixprofile.org/posts/how-to-painlessly-analyze-your-time-series/   
https://www.cs.ucr.edu/~eamonn/MatrixProfile.html   
https://github.com/TDAmeritrade/stumpy   
https://franzbischoff.github.io/tsmp/   

### Ocean Data Sources
https://tos.org/oceanography/article/using-authentic-data-fromnsfs-ocean-observatories-initiativein-undergraduate-teaching-an-invitation   
https://oceanobservatories.org/   
https://datalab.marine.rutgers.edu/   

### Python
https://www.python.org/   
https://wiki.python.org/moin/BeginnersGuide/NonProgrammers   
https://datalab.marine.rutgers.edu/2020/11/introduction-to-python-data-analysis/   
 
