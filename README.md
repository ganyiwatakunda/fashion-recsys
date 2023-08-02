# fashion-recommender-system
This is a model of a Fashion Recommender System using the KNearest neighbor algorithm to make predictions. This sysytem allows users to input a sample images e.g shirt or trousers and the functionality of the model is to output 5 images that are most closest or similar to the inputted image. This is of a great advantage as it helps one to chose what he really wants and it makes easy the process of e-buying, by recommending images. 


## Getting started

1. clone or download this repository in your prefered notebook e.g colab
```sh
!git clone https://github.com/ganyiwatakunda/fashion-recsys.git
```
2. run the main.py file on streamlit to experiment the functionality of the app
```sh
!streamlit main.py
```
5. once prompted by the program, click on the browse files and input an image, you want to use for recommendations
## Demo

Here is the welcome page of the Fashion Recommendation System :
![demo image of running program](https://github.com/ganyiwatakunda/fashion-recsys/blob/master/demo/open.png)

### final output of demo:

![demo image of running program](https://github.com/ganyiwatakunda/fashion-recsys/blob/master/demo/Frontdemo.png)


## Implementation
I used NLTK's probability library to store the probability of each predicted word,
```sh
ConditionalFreqDist()
```
then the program picks from a weighted random probability to decide which prediction to append to the given phrase.
```sh
random.choices()
```
The user decides when to stop the program by choosing whether or not to predict the next word.
```sh
"Do you want to generate another word? (type 'y' for yes or 'n' for no): "
```
