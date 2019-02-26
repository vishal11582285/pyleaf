# LeafAreaCalculator
ComputerVison and Machine Learning: Convolutional Neural Network to compute leaf area

This project was a free lancing project for School of Biological Science at Washington State University.
The goal of the project was to detect number of pixels that would potentially consitute a leaf. These 'green' pixels fraction as compared to a known
quantity computes the area (cm^2). This constitues to a classification problem over image object.

Steps:
1) Train CNN model to learn various levels of green, red and arbitrary pixels. [Note any other color except green and red is of no particular
interest to us, hence classified as arbitrary.
2) Break the image as list of pixels and classify them in a supervised training fashion. [Select pure green leaf images placed in 'green' folder, pure 'red' images in 'red' folder, etc]
3) Compile and save the model that tests with an acceptable accuracy. [Accuracy obtained: 95 %].
4) Knowing that the number of pixels in every image is 4 cm^2, we computed the leaf area as number of green pixels ~ number of red pixels [whose areas is known].

The project was implemeneted using Python Keras/Tensorflow libraries and OpenCV/color packages.
A substantial advantage of this program was, due to the state of the art CNN machine learning algorithm used, leaf object with varied
intensities of green were classfied with supreme accuracy. The raw images were generated through different sources, scanner and DSLR camera,
but due to the algorithm logic, these differences were incorporated and computation did not result in loss of records.

This algorithm has been successfully run on atleast 3500+ images and has helped the research lab save valuable time and energy 
otherwise invested in manual efforts.
