# Detection-of-Leaf-Diseases-using-CNN-Model

## Objective

Detection of various diseases in leaves using CNN Model.


## Tools and Libraries

The application is made up of a number of libraries that make use of a variety of tools and datasets. They all play an important role in the development of the entire application, including the optional interfaces. The following are some of the libraries, tools, and datasets that can be used with it:
1. Google Colab: We used Google Colab to do this project as it provides even more preinstalled machine learning libraries such as Keras, TensorFlow, PyTorch when compared to anaconda navigator
2. TensorFlow is an open source platform to build models with large-scale networks with many layers.
3. Keras: An open-source neural-network library that lets users turn deep models into products. It is utilized in the application to anticipate the sentiment of patients.
4. OpenCV: It's a Python bindings library aimed at solving challenges in computer vision.
5. NumPy: It is a library that contains multidimensional array objects as well as a collection of array processing routines.
6. Python: It's a high-level, interpreter-based general-purpose programming language. It's garbage-collected and dynamically typed. It supports a variety of programming paradigms, such as structured object-oriented programming and functional programming. It comes with a large standard library. This programming language is used to create the application.

## Developed Methodology

Image Processing : It is the application of a set of methods to an image in order to improve it or extract useful information from it. Acquisition, Segmentation, Augmentation, and Feature Extraction are all stepsin the acquisition process. The initial stage in digital image processing is image acquisition. Whenan image is already in digital form, image acquisition is a simple operation. The image acquisition stage frequently includes preprocessing, such as scaling. Image segmentation procedures separate an image into its component portions or objects. Autonomous segmentation is the
most difficult problem in digital image processing. A powerful segmentation technique that helps solve image issues requiring individual object recognition. A technique for artificially increasing a dataset is image augmentation. To enhance the number of data samples, zoom, shear, rotation, preprocessing, and other features are routinely used. One of the most significant parts of this project is image feature extraction. Feature selection selects the best features based on statistical tests that aren't uniform. The characteristics are carefully chosen based on their distinct variances betweenthe various varieties of leaves.

CNN Model : CNN is a widely used image recognition technique that has been shown to attain greater than 78.1 percent accuracy on the ImageNet dataset. The model is the synthesis of numerous academics' ideas developed throughout time. A 256x256x3 input represents a 256-pixel visual field with three color (RGB) channels. Five convolution layers, with a few max-pooling processes strewn throughout. Stacks of "CNN Models" after stacks of "CNN Models." After the mixed layer, there is a SoftMax output layer at the end of an intermediate output layer. The steps involved in CNN are as follows: CNN uses a filter to conduct convolution layers on an input image. The Relu (Rectified Linear Unit) simply transforms all negative numbers to 0 while maintaining the positive
values. The Convolved Feature's spatial size is reduced by using a pooling layer. They are divided into two types: maximum pooling and average pooling. Fully interconnected layers in a neural network are those in which all of the inputs from one layer are connected to each activation unit of the next layer. The cross-entropy loss system is widely used to train these networks, resulting in a nonlinear variation of multinomial logistic regression.

## Detected Diseases

(1) Bell PepperBacterial Spot, Xanthomonascampestris
(2) Bell Pepperhealthy
(3) Potato Early Blight, Alternariasolani
(4) Potato healthy
(5) Potato Late Blight, Phytophthorainfestans
(6) Tomato BacterialSpot, Xanthomonascampestrispv. vesicatoria
(7) Tomato EarlyBlight, Alternariasolani
(8) Tomato Late Blight, Phytophthorainfestans
(9) Tomato Leaf Mold, Passalorafulva
(10) Tomato SeptoriaLeaf Spot, Septorialycopersici
(11) Tomato Two Spotted Spider Mite, Tetranychusurticae
(12) Tomato Target Spot, Corynesporacassiicola
(13) Tomato Mosaic Virus
(14) Tomato Yellow Leaf CurlVirus
(15) Tomato healthy

## Conclusion

For identifying and classifying, an automated system has been built. The correct identification and classification of plant diseases is critical for successful crop cultivation. This research will extract the properties of the affected leaf using classification techniques, and then diagnose the plant
diseases with more accuracy. It will assist farmers in increasing their profits. Image processing could be utilized in agriculture for a variety of applications. It entails detecting diseased leaves, measuring the diseased area, and determining the color of the afflicted area. This solution will be
especially valuable in places where disease identification knowledge is lacking, such as newcomers to agriculture and people who produce plants and crops at home. The number of affected crops is predicted to decrease once this approach is fully operational. In recent years, there has been a major growth in scientific literature devoted to employing image analysis to detect stress in plants. Disease identification is an important part of agricultural plant management in agriculture. Farmers would benefit from early detection of stress and pathogens since it would allow for earlier actions to help limit crop loss and improve crop quality. Plants are scanned to acquire high-resolution data in the imaging process. The technology has grown in popularity as the cost of camera production has decreased, giving researchers and developers more access to it.
