# Text-Summarizer
## About
An Abstractive text summarizer trained using lstm based sequence to sequence model with attention mechanisim. The attention model is used for generating each word of the summary conditioned on the input sentence.

Used CNN_DailyMail dataset.
### Training Model Overview
loss graph

![train_log](https://user-images.githubusercontent.com/115065702/194541908-30cb640c-4c61-45c8-ae15-204cf28fd06c.jpg)

encoder-decoder overview
![model_plot](https://user-images.githubusercontent.com/115065702/194541983-48da00c8-30c6-45c7-b963-c7bc1600fd39.jpg)
#### Conclusion
🫶 The machine learning model to convert a text document to abstract is done successfully.

🫶 Created a Flask app using an api call from my hugging face repository & deployed the app in heroku app.
##### Deployment:
![SS1](https://user-images.githubusercontent.com/115065702/194542220-8982a381-1e41-42df-bdb2-7956635fcd16.jpg)

🫶 https://text-summariser-v1.herokuapp.com/
