# RPCA_Project_Code_Team_2
# Jennifer Camacho, Octavia Larentis and Lauren Picado

This project implements the Robust Principal Component Analysis method using the Principal Component Pursuit (PCP) and Stable Principal Component Pursuit (SPCP) that rely on the Augmented Lagrange Multiplier (ALM) method and Accelerated Proximal Gradient (APG) method respectively.

The code folder holds two Jupyter notebooks files from which the code is run, with the main functions rpca_pcp, rpca_spcp, rpca_pcp_vary and rpca_spcp_vary serving to process video image frames using the PCP method, SPCP method, PCP method with decreasing penalty parameter and SPCP method with decreasing penalty parameter found in rpca_video_processing.ipynb.

The input images were sourced from the the Change Detection repository at http://changedetection.net (CDNET). The variety of image sets used include moving pedestrians, traffic camera footage and a person working in an office. The input frames are found in the highway, pedestrian and office folders respectively. The ground truth frames provided by CDNET are found in highway_groundtruth, pedestrian_groundtruth and office_groundtruth. The ground truth image frames were pre-processed to remove multiple gray levels that represented areas of ambiguity and the output saved to highway_G, pedestrian_G and office_G.

The statistical analysis was performed using the functions listed in rpca_statistical_analysis.ipynb.
