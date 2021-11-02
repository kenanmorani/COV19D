# COV19D
The project includes working on a chest CT-scan series of images aiming to develop an automated classification algorithm for Covid-19/non-Covid-19 diagnosis. The project is towards the international COV19D cmmpetetion described in section B at https://mlearn.lincoln.ac.uk/mia-cov19d/.
Images are all in JPG fomrat.

## The codes
The codes develop deep learning classification models and Transfer Learning Based Classification Models:          
1. Deep Learning CLassification Models: 
<br /> A) The Code '3D_Image_Classification_binary_cross_loss.ipynb' introduces a CNN model solution for COVID-19 diagnosis from CT-Scan images.
<br /> B) The code '3D_Image_Classification.ipynb' introduces a classification method based on a CNN model with Macro f1 as a loss function.
<br /> C)The code '3D_Image_Classification_with_Modified_UNET_Architecture.ipynb' introduces a classification solution by a deep learning model, which is a modification of UNET model architecture.

2. Transfer Learning Based Classification Models:
<br /> The code 'Transfer_Learning_VGG16_RF.ipynb' introduces a transfer learning method using VGG16 model for feature exctraction followed by Random Forest  classifier to take the final classification dicision.


