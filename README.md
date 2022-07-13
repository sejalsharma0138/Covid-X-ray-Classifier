# Covid-X-ray-Classifier
TASK: The task was to code a neural network that can classify between healthy and infected lungs using their X rays’ data from the images provided. 

DATASET:The COVID radiology from Kaggle which included around 16,000 images of X rays of infected patients around the world.
The data set included four categories COVID, pneumonia, healthy and lung opacity. 

MODEL:The categories apart from COVID are combined into a single category so that more examples of diseases other than COVID can be given to the
neural network for learning.
The step for creating neural network includes exploratory data analysis, creation of data frames in accordance with the problem which included paths of 
the images according to the various categories, and data augmentation steps took place using the keras image preprocessing library.

Data generators were created to load images from the paths and model was finally trained with this data.  
Metrics like accuracy and precision were measured to gain more insights into the model

Training data
![train][https://github.com/sejalsharma0138/Covid-X-ray-Classifier/blob/main/Training%20samples.png]

Training and Performance Plots
![plots][https://github.com/sejalsharma0138/Covid-X-ray-Classifier/blob/main/Training%20and%20performance%20slots.png]

Results
![res1][https://github.com/sejalsharma0138/Covid-X-ray-Classifier/blob/main/Precision%20results%20per%20class.png]
![res2][https://github.com/sejalsharma0138/Covid-X-ray-Classifier/blob/main/recall%20and%20f-score.png]
