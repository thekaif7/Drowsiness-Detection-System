
# Drowsy Driving Problem:
Drowsy drivers may cause nearly a third of all deadly car crashes according to federal statistics and a study at the University of Pennsylvania Health System proves the danger. According to Dr. Michael Grandner “A lot of people don’t realize that more serious crashes are caused by falling asleep at the wheel than alcohol”. “Though we’ve all heard of drunk driving, we haven’t heard much about drowsy driving, but it’s a major health problem and safety problem.” Dr. Grandner, a member of the Center for Sleep and Circadian Neurobiology, says a survey of more than 17,000 people showed that most people need at least seven hours of sleep each night. While distracted driving has been getting a lot of attention lately, drowsy driving remains a major risk for motor vehicle crashes.
Two out of every five drivers (41%) admit to having fallen asleep at the wheel at some point. One in ten said they have done so in the past year according to a new AAA Foundation for Traffic Safety Study.
One in six (16.5%) of deadly crashes, one in eight of crashes resulting in a hospitalization, and one in eight out of fourteen crashes in which a vehicle had to be towed involved a drowsy driver.
The National Highway Safety Administration estimates that drowsy driving results in 1,550 deaths, 71,000 injuries and more than 100,000 accidents per year.
More than half (55%) of drivers who reported falling asleep while driving in the past year said they had been driving for less than one hour before falling asleep.
Many traffic researchers believe drowsy driving has been under-reported and underestimated.

Driver’s status is crucial because one of the main reasons for motor vehicular accidents is related to driver’s inattention or drowsiness. Drowsiness detectors on a car can reduce numerous accidents. Accidents occur because of a single moment of negligence, thus a driver monitoring system which works in real-time is necessary. This detector should be deployable to an embedded device and perform at high accuracy.
Detecting the drowsiness of the driver is one of the surest ways of measuring driver fatigue. In this project we aim to develop a prototype drowsiness detection system. This system works by monitoring the eyes of the driver and sounding an alarm when he/she is drowsy.

# Proposed Method
Conventional machine learning techniques rely on designed feature extraction algorithms which attempt to summarize the source data. The summaries are then fed to classifiers to reach conclusions. Convolutional Neural Networks (CNN) have proved a robust and precise ability to extract features and reach a conclusion, without the need for user design or intervention. CNNs were first inspired by cat’s visual cortex and are built from multiple layers performing conventional transforms with parameterized filters, followed by decimation through pooling and ending with a fully connected convolutional network for final classification. An illustrative representation of a CNN is shown in Fig. 1. 
The given network consists of seven layers starting from the input layer. We provide the layer size and the number of color channels on the figure. The input image is convolved with multiple filter kernels in the convolution layers. Filter weights are learned. The output volumes of the convolutional layers are processed by the next pooling layer for downsampling. The idea is to reduce the size while maintaining important information. Reducing the size reduces the number of trainable parameters. The most common form used is max pooling. Convolutional layers followed by pooling layers form a pair or a block. The depth of the network is achieved by adding (repeating) more of these blocks. The generated feature maps from sequential convolution and pooling layers need a fully connected layer at the end which uses the summarized information produced so far (automatically produces feature space) to generate an output equal to the number of classes in our classification problem.
CNN performs better when trained on very large data sets. Transfer learning allows researchers to reduce the demand for data by starting the search for the optimum parameters for the problem in hand from initial conditions obtained through searching for other similar problems where the data is available. For example, transfer learning on a data set already trained on faces reduces the need for data to practical levels.

![alt CNN model architecture](https://github.com/thekaif7/Drowsiness-Detection-System/blob/master/readme/modelArch.jpg?raw=true)
<p align="center">CNN Model Architecture</p>

![alt Result](https://github.com/thekaif7/Drowsiness-Detection-System-using-CNN/blob/master/readme/out.png?raw=true)
<center>Model Prediction</center>
