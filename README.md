The code 'GUV_detection' analyses multichannel (2-4 colors), multislice (80 slice z-stack), multitile (optional) .czi files of size 512x512 pixels.
Folder path and channels for GUV and dye detection have to be specified. 
The code's output is a folder with overlay images of detected GUVs and a .csv summary with the measured values.

The codes 'LeastSquare' and 'VesicleSettling' calculate, plot and analyse how GUVs sediment in different environments. 
Simulations are compared to experimental data which is given as a .csv file called 'input_Fig2e_experimental_data'.
One can play around with conditions and simulation settings. The current parameters are the ones used to plot Fig. 2f and Supplementary Figures 4, 15 and 24.

The script is run on Jupyter Notebook.
Python version 3.10.14 is required.

Demo .czi data: https://heibox.uni-heidelberg.de/d/77aeaf76e9c54fd8a1c7/
The script runs several seconds on a normal desktop computer for this demo file. 
