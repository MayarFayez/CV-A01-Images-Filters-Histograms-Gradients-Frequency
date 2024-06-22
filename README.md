# CV-A01: Images, Filters, Histograms, Gradients, Frequency

## Description:
A small web application based app developed with python and streamlit, to apply different image processing techniques.

## Requirements:
• Python 3.  
• Streamlit 1.13.0  
• Numpy 1.23.4  
• Scipy 1.9.2  
• Matplotlib 3.6.2  
• Seaborn 3.6.2  

## Running command:
Streamlit run server.py 

-The UI contains three main tabs filtering, histogram and hybrid images.

# Tab1:
• Noise  
• Filters  
• Edge masks
### Noise:
1. Uniform noise
Using uniform distribution  
![Screenshot (1437)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/c57280a0-206b-48a5-af6a-e917b9ca9688)  
Result  
![Screenshot (1438)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/df5e17a8-34f1-41d3-a9cc-bce98a73be66)

2. Gaussian noise  
Using Gaussian distribution
![Screenshot (1439)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/c22dab35-d545-47a4-9c70-531ebd14f940)  
Result  
![Screenshot (1440)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/0b0dbb43-a038-4fb7-8ef7-110ea20978b5)

3. Salt and pepper noise  
Result  
![Screenshot (1441)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/cd7d1509-c03a-408a-9714-af7bbaa7eb65)

### Filters:  
1. Average filter  
It uses 3 x 3 kernel which is convolved with the input image to calculate output.
![Screenshot (1442)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/27f79e6e-720d-427c-8be7-ca0bbc82bd2d)  
Parameters: Kernel_size  
Result  
![Screenshot (1443)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/ca425ae1-1fa0-4865-815d-ddc0fd9b49ed)  

2. Gaussion filter  
The formula to design gaussian kernel.   
![Screenshot (1444)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/3865e52b-7a6e-46dc-9641-860e301c82b4)   
Example:   
![Screenshot (1445)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/3e3c2394-13f5-4708-8ddb-152ab5b604b7)  
It uses gaussian kernel which is convolved with the input image to calculate output.  
Parameters: Kernel_size,sigma  
Result  
![Screenshot (1446)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/240a86bc-f956-44b1-ac71-fe70da99cbc1)  

3. Median filter  
![Screenshot (1447)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/54091c6c-4d9f-4fd2-ba61-3cdc266dddf5)  
Parameters: Kernel_size  
Result   
![Screenshot (1448)](https://github.com/MayarFayez/CV_-HPF-LPF_-Techniques-/assets/93496610/d856bc89-c41e-488e-90fe-d88333f58b0d)  

Note    
-The larger the kernel size, the greater the smoothing.      
-Median filter is the best filter for salt and pepper noise.    

### Edges:
Edges are significant changes in intensity of pixels of digital image. There are 
3types of edges: horizontal, vertical and diagonal. Edge detection is segmentation 
into regions of discontinuity, there are 2 types of operators:  
 Gradient: compute 1st order derivative like Sobel, Prewitt and Roberts.  
 Gaussian: compute 2nd order derivative like Canny.  

















