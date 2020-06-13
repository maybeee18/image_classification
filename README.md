# image_classification
## DL-Model-Flask-Deployment
This is a demo project to elaborate how Deep Learning Models are deployed on production using Flask API

### Prerequisites
You must have keras, tensorflow, sklearn, seaborn, matplotlib, numpy and Flask (for API) installed.

### Project Structure
This project has three major parts :

1. flowers_image_classification.ipynb - This contains the code implemented to the train the deep learning model from scratch on the categories of flowers considered. This file also contains the model_plot, confusion matrix plots for in-depth analysis.
2. app.py - This contains Flask APIs that receives images through GUI or API calls, computes the labels based on our model and returns it.
3. images - these are the images that were used as input to train the classifier.

### Running the project
1. Ensure that you are in the project home directory. Open the deep learning model notebook 'flowers_image_classification.ipynb' for more information

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

Upload the image and check for the output value returned by the model.
