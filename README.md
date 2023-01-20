# DCF

## Image Completion via Dual-path Cooperative Filtering  
##### (The codes and the pretrained weights will be uploaded soon.)



### DCF Architecture

<a href="http://tensorlayer.readthedocs.io">
<div align="center">
	<img src="Img/1.png" width="40%" height="40%"/>
</div>
</a> </pre> </pre> <br />


### Results


<a href="http://tensorlayer.readthedocs.io">
<div align="center">
	<img src="Img/2-1.png" width="75%" height="65%"/>
</div>
</a> <br /> <br />

<a href="http://tensorlayer.readthedocs.io">
<div align="center">
	<img src="Img/3.png" width="75%" height="65%"/>
</div>
</a> <br /> <br />



### Prepare Data

The dataset can be downloaded from this [kaggle link](https://www.kaggle.com/insaff/massachusetts-roads-dataset). Some of the images in training set does not have corresponding masks. The training code filters out those images. All the images are of size 800x800. Code for data analysis is in this notebook. 
  
