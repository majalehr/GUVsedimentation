The code analyses multichannel (2-4 colors), multislice (80 slice z-stack), multitile (optional) .czi files of size 512x512 pixels.
Folder path and channels for GUV and dye detectio have to be specified. 
The code's output is a folder with overlay images of detected GUVs and a .csv summary with the measured values.

The script is run on Jupyter Notebook.
Python version 3.10.14 is required.

Demo .czi data: https://heibox.uni-heidelberg.de/d/77aeaf76e9c54fd8a1c7/
The script runs several seconds on a normal desktop computer for this demo file. 
