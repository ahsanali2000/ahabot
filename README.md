# AhaBot
## Self Attention based knowledge space aggregator bot 


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## HOW TO RUN:
- Place the `label_encoder.pickle`, `chatbot_model.h5` and `tokenizer.pickle` in the root folder.
- run `pip install requirements.txt`
- then run `python manage.py runserver` to start the server. 
- simply open `index.html` in interface folder. You can now interact with our chatbot :)


## FEATURES:
- Our ChatBot allows you to create diverse knowledge base merely from a list of FAQs and automatically handles user requests in real time.
- The model is intelligent and doesn't require hardcoded values. 
- It is equipped with deep transformer neural networks to create a knowledge space for each question to model similar meaning situations. This is the core feature of our chatbot as this not only augments the data, it also allows you to handle a diverse set of requests.
- You can either the pre-trained model `chatbot_model.h5` or retrain the model on your custom FAQs.

## Sample Output:

## About Code:
- We are using neural networks, deep transformer neural networks and BERT embeddings in our model.
- The model runs for `350` Epochs and gives `95%+` accuracy with `< 0.05` categorical loss.
- `vanilla javascript` was used for front end.
- `Django` was used for backend.
- The model contains `16000+` trainable parameters and uses the power of tensorflow to train on it.
- `After the modle is done training, the encoding files and model weights are saved. You don't have to go through the hassle to retrain it every time.

Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨
