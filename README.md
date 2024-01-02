# Social-sleep
Image datasets used to establish the hyper-parameter threshold for physical contact (Sotelo et al. Neurophysiological and behavioral synchronization in group-living and sleeping mice. 2023). 
Brifly, we initially generated a training set by randomly sampling frames from our entire dataset. We manually excluded frames where the outlines of the mice bodies were occluded, which hindered a clear determination of whether the mice were touching or not. Subsequently, we manually classified the images as depicting either ’physical contact’ or ’no physical contact,’ resulting in 935 ‘physical contact’ frames and 1178 ’no physical contact’ frames. 
Then, to assess different hyper-parameter thresholds, we generated three test sets by randomly re-sampling our dataset (excluding images used for training), testing three distinct threshold values for physical contact: 4 cm, 5 cm, and 6 cm. Once again, we excluded frames where the outlines of the mice were obscured, yielding 1988, 2037, and 2020 frames for the 4 cm, 5 cm, and 6 cm thresholds, respectively. 

Image datasets: https://drive.google.com/drive/u/0/folders/1W84u3Bh84A9086Ngw0Zlk8HGlB5ZGUnQ?ths=true
