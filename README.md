## - Gesture Recognition Assignment

##### 1. Elayaraja Muthuraj
##### 2. DineshKumar




### Problem Statement
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
 
| Gesture | Corresponding Action |
| --- | --- | 
| Thumbs Up | Increase the volume. |
| Thumbs Down | Decrease the volume. |
| Left Swipe | 'Jump' backwards 10 seconds. |
| Right Swipe | 'Jump' forward 10 seconds. |
| Stop | Pause the movie. |

Each video is a sequence of 30 frames (or images).

### Objectives:
1. **Generator**:  The generator should be able to take a batch of videos as input without any error. Cropping, resizing and normalization are performed successfully.

2. **Model**: Develop a model that is able to train without any errors ,the optimal total number of parameters and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

3. **Summary Write up**:Contains  complelete procedure for choosing the final model. The summary inlcudes the reason for choosing the base model, then the reasons and metrics of consideration to modify and experiment to arrive at the final model. 


### Installation:
Run ***pip install -r requirements.txt*** to install all the dependencies.

I choose CNN+LSTM based model as the final choice due to fairly decent accuracy considering the type of data as well the no. of parameters as I wanted my model to be light weight in nature.

BY:
https://github.com/Elaya1984


