# Delibird Drive Mode
This repository is about Delibird's Driving Mode.  
We have 2 Driving Mode.
# Auto SLAM
Auto SLAM is about autonomous drive using SLAM.  
Using Frotier Exploration Algorithm, Delibird can autonomous drive and make map.  
![Frontier Exploration](http://robotfrontier.com/frontier/images/grid-key.gif)    
When we launch the auto slam, the robot can autonomous drive.
Implementation of frontier exploration for ROS, extending on the existing navigation stack (costmap_2d, move_base). It accepts exploration goals via actionlib (Rviz UI provided), sends movement commands to move_base.
# Auto Clean Drive
This package provides an implementation of a Full Coverage Path Planner (FCPP) using the Backtracking Spiral Algorithm (BSA).  
![Clean Image](https://lh3.googleusercontent.com/fife/AAWUweUQ2TLH7vS41YvRyMbMQcowh5hYNXaXD9KfMr6jqFsKHkR7htdCpVdq1Y_33U-K18mC3Ug-LllZUsmUmYYIJ7scIYTwkz-1X-bLZZ_ShbQ3SgW_sC7Mrw3pT46DWsqbbp_MB04lVq0ylPo1_G6v87WNvih1JeKwVhHajYziIPaqimiZ6urBG3fJGw9wl8KNPNzbTd3mDwT16RS6_pTL9YmqzRuwjJ1VIWoH4uM0Ng26wY9WmZRKBZwy1OQmTmvIJZIahRk9SKaut1q0VpF3yGSKx6mUXamoqpERkRCSYspOHIENQRnqw0HLLslTp6XxYDqMfN_1zt_lSgpaY8wHmNRTae1Kmb5FVKsd5jTvBqVwHL8NajbhyL9CzYKmEvlUUU3-243GejINhxQZjSESxl-E6azhupOPmeJy7TdYHV3ol3XODfdhzTSUolkwTscZcNpWd9ESHufmYYGCGq5ZsG6BbcqbtWo9OrukJIzfjMFeBmfV3iEaR50kTI52GsB520dQGEPvDxJEvG53YI2yJ7zfKxKLhvLBmkEQrRwxGzznN53ovSnP7p47Ydb4RLBSoTmpANPSjgwhuYBjQcSMKoMuw16o3yCtJFob06WvVWQ3yeN2iwKQK-tHgYDLSJbShhAdX3KYV4goThIBCAQY--W2qGv4xPk9NetkpB3PggoY9RyeUoNk3g0GSjWfXn44UeaATushkbMA97dX4yMJPh5a7hl4xP2MsA=w1920-h937-ft)  
When we launch the clean work, the server calculate the full coverage path. Then, the robot moves along the path.  
