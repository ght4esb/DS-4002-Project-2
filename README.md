# DS-4002-Project-2
This project uses a convolutional neural network (CNN) to identify digital images of handwritten digits with an accuracy rate of 90.88% . The model uses thousands of handwriting examples from American Census Bureau and American high school students contained in the Modified National Institute of Standards and Technology (MNIST) dataset. This project is motivated by the time consuming and expensive task of manual digitzation of documents. Addressing this problem increases access to numeric data online, providing benefits of greater access to people with disabilities and convenience.  

## SRC 
### Installing/Building Code
We accessed the MNIST data set through the Keras package and read it using Google Colab. The data set contains 60,000 training images and 10,000 testing images of handwriting for online handwriting recognition. We reshaped the data into a 28 x 28 pixel box to isolate letters. We then created the model [1].

### Usage of Code
We trained the model using 30 epochs. We evaluated the model by creating a graph comparing the validation and accuracy of the model [2]. We refined the number of epochs by observing the test loss and test accuracy. We also compared the test loss and test accuracy values to our hypothesis. Finally, we created a visual representation of a sample of letters and compared the computer's prediction for each letter to the true letter value.
 
## Data 

Data Dictionary
|Column Name|Definition                                                                                    |Data Type      | 
|-----------|----------------------------------------------------------------------------------------------|---------------|
|Offset |Per-row bias value                                                         |String         |
|Type |Integer or byte                                                        |String         |
|Value       |Numbered value                                                               |Integer        |
|Description      |Description of rows |String         |

[Link to data](https://www.tensorflow.org/datasets/catalog/mnist)

### Relevant Notes about the Use of Data
This dataset is contained in the Keras package. This makes obtaining and using the data convenient. However, the dataset is large. Training the model took over an hour depending on computing power. This challenge may be overcome by using more powerful computers.

## Figures 
Table of Contents
|Figure     |Key Takeaways| 
|-------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Figure 1 Model Accuracy                   | Optimal number of epochs is 30. |
|Figure 2 Results | Result XYZ|



## References
[1] S. Gupta. “Newbie’s deep learning project to recognize handwritten digits.” Analytics Vidhya. https://www.analyticsvidhya.com/blog/2021/11/newbies-deep-learning-project-to-recognize-handwritten-digit/ (accessed March 17, 2023).
[2] Daniel. "How to plot model loss during training in TensorFlow." Medum.com. https://medium.com/geekculture/how-to-plot-model-loss-while-training-in-tensorflow-9fa1a1875a5

### Links to MI1 and MI2
[MI1](https://docs.google.com/document/d/1tOLzCnjqewWEiW7LgYi7sEt7-VsKjKqJq9toB5s7deQ/edit)  
[MI2](https://docs.google.com/document/d/1tOLzCnjqewWEiW7LgYi7sEt7-VsKjKqJq9toB5s7deQ/edit)
