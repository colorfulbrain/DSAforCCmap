# DSAforCCmap
<br />The example of CCmap and Tmax map is illustrated in the jupyter notebook file.
<br />Here are the steps for mapping the CC and Tmax of blood flow in the ICA.
# Steps
## Download and unzip the DICOM files 
<br />After unzip, the file name should be ImageFileName05.dcm.
## Run Python codes
<br />1. install opencv, skimage, pydicom in the python
<br />2. replace _skeletonize.py in your python skimage package (maybe in python3.8/site-packages/skimage/morphology/_skeletonize.py) with _skeletonize.py in the git directory
<br />3. keep ImageFileName05.dcm and ForGIT_codes4mapping_CC_Tmax.ipynb in the same directory
<br />4. run  ForGIT_codes4mapping_CC_Tmax.ipynb
