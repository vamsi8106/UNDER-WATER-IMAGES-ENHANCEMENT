
# UNDER-WATER-IMAGES-ENHANCEMENT
## Abstract
Underwater images find application in various fields, like marine research, inspection of aquatic habitat, underwater surveillance, identification of minerals, and more. However, underwater shots are affected a lot during the acquisition process due to the absorption and scattering of light.Hence, underwater images need enhancement to improve the quality of images to be used for various applications while preserving the valuable information contained in them.

Objectives- 
- To enhace underwater images for reserach purpose to explore acquatic system.
- To study various methods available for enhancing under water images.

## Methods for under Water image enhancement- 
### spatial domain techniques are
1. Blur and Sharpen filters
2. Histogram Equalisation
3. Clahe Filter
4. Laplacian Filter
5. High Boost Filter
6. Bilateral Filter
### Frequency domain techniques are 
1. Ideal Low Pass and High Pass Filters
2. Butterworth Low Pass and High Pass Filters
3. Gaussian Low Pass and High Pass Filters
4. Homomorphic Filter
5. Wavelet Transform
### Some Other techniques tried are
1. Denoising Filter
2. Neural Network


### Steps to run the project files- 
Image data set:https://drive.google.com/drive/folders/1N0i6OxNmk2QOTvJS857XZKjsOyLA9nUS?usp=share_link   
These images are taken from  http://umpir.ump.edu.my/id/eprint/26347/
- Enhance the under water images using a suitable method as per required application. 
- Use the "CV_PROJECT_1.ipynb" file to enhance the images. 
- Make sure u downloaded below mentioned files before running CV_PROJECT_1.  
   Colorization model reference https://github.com/balajisrinivas/Colorizing-black-and-white-images-using-Python/tree/master  
   
   Image Enhacement measures reference https://github.com/andrewekhalel/sewar/blob/master/sewar/full_ref.py

### Results
Input Image   
![1](https://user-images.githubusercontent.com/99885183/226164723-d9d8bf2f-71db-40b3-923a-d418beb7e331.jpeg)  
Output Image  
![output_hist](https://user-images.githubusercontent.com/99885183/226164840-1d6e8164-5bbd-4f03-82c9-5809a1d62bb3.jpeg)

<table>
  <tr>
    <td>First Screen Page</td>
     <td>Holiday Mention</td>
     <td>Present day in purple and selected day in pink</td>
  </tr>
  <tr>
    <td><img src="![ideal_lpf](https://user-images.githubusercontent.com/99885183/226165007-058beb65-b587-4f85-a40e-b8fc06cce168.jpeg)
" width=270 height=480></td>
    <td><img src="![hist_equ](https://user-images.githubusercontent.com/99885183/226165029-3cd129cc-72a5-4f54-9879-63357f045575.jpeg)
" width=270 height=480></td>
    <td><img src="![output_lpf](https://user-images.githubusercontent.com/99885183/226165050-471901cb-6abe-43b7-82cf-dc9035538567.jpeg)
" width=270 height=480></td>
  </tr>
 </table>

### Dependencies

-OpenCV  
-NumPy  
-Matplotlib  
-tensor flow  

