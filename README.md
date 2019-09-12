# Image-Masking-via-EPI
Accurate image masking via EPI and edge detection in small lab setting environment 
<p>Contact: <a href=mailto:c.sathirasethawong@student.adfa.edu.au>Chawin Sathirasethawong</a> (<a href=mailto:chavinsdz@gmail.com>chavinsdz@gmail.com</a>)
<p><b>Abstract</b>
  <br>In automated photogrammetry of a small object, rotating the object provides an easier setting and more stable camera positions than moving the cam-era around the object. However, the static features in the background can confuse the structure from motion, which leads to the failure of reconstruction. We are addressing the problem by proposing a masking algorithm based on light field epipolar-plane images (EPIs). Using a simple EPI analysis and edge detection technique, a single light field image is enough to create an initial mask, which acts as a region of interest for an edge image. Lastly, binary morphological tech-niques are applied to obtain the final mask image. The result shows promising performances of 93.84% recall and outperforms comparable algorithms in accu-racy, precision, JI, and F1 scores with 98.39%, 97.75%, 91.86%, and 95.75%, respectively.

# Dataset
We provide the dataset which includes raw light field images in LFR format with camera calibration files, and comparable result images and groundtruths. <a href=https://cloudstor.aarnet.edu.au/plus/s/yFN89S5oaxGccnh>Download</a>
<p>This dataset is provided as part of the following publication:
<p>Sathirasethawong, C., Sun, C., Lambert, A., Tahtali, M.: Foreground Object Image Masking via EPI and Edge Detection for Photogrammetry with Static Background. In: International Symposium on Visual Computing (ISVC), Springer, (2019). (Pre-print)
<p>Please cite the above paper if you use any part of the images or results included in the dataset. 
<br>Please see the project page for more information: https://github.com/Chawin-S/Image-Masking-via-EPI/ 
  <img src="https://raw.githubusercontent.com/Chawin-S/Image-Masking-via-EPI/master/04avzcU.png" width=10% height=10%>
