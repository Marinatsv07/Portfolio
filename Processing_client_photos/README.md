# Processing Client Photos: Determining the Age of Buyers

## Project Description
The Bread-Sol supermarket chain is deploying a computer vision system to process customer photos at checkout areas. This initiative seeks to determine customers' ages for two primary reasons: to tailor product recommendations based on age-related purchasing patterns and to ensure compliance with legal age restrictions on alcohol sales. This project revolves around constructing a model that estimates a person's age from their photograph.

## Data
The dataset comprises photographs of individuals, with each image annotated with the subject's age. This collection will be used to train and validate the age estimation model.

## Project Objectives and Tasks
The objective is to develop an accurate model that can deduce a customer's age from their photograph. The project encompasses the following tasks:
1. **Conduct an Exploratory Data Analysis (EDA) of the Photo Dataset**: Assess the dataset to understand the age distribution, image quality, and other characteristics that may influence the model's training and performance.
2. **Prepare the Data for Training**: This involves preprocessing the images to a uniform size and format, augmenting the dataset to improve model robustness, and splitting the data into training, validation, and test sets.
3. **Train a Neural Network to Estimate Ages**: Leverage a convolutional neural network (CNN), potentially starting with a pre-trained model like ResNet50, and fine-tune it for the age estimation task.
4. **Evaluate the Model's Performance**: After training, assess the model using appropriate metrics, such as mean absolute error (MAE) between the predicted and actual ages, to determine its accuracy and reliability.

## Skills and Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Keras with TensorFlow

## General Conclusion

In this project, I loaded images and ages, created a neural network with ResNet50, and trained it. The final model achieved a Mean Absolute Error (MAE) of 6.4589 and a Mean Squared Error (MSE) of 70.8945, indicating it predicts ages with an average error of about 6.5 years. This performance aligns with goals  of the project for analyzing customer purchases and monitoring alcohol sales integrity, providing a solid foundation for further enhancements.
