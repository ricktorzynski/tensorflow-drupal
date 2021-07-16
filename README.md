# tensorflow-drupal
Repository for Drupal ConGov monthly meeting July 16th, 2021

# Building a Recommender System Using Drupal and TensorFlow.js
Adapted from *Build, Train, and Deploy a Book Recommender System Using Keras, TensorFlow.js, Node.js, and Firebase (Part 1)*, https://heartbeat.fritz.ai/build-train-and-deploy-a-book-recommender-system-using-keras-tensorflow-js-b96944b936a7.  Instead of using Node.js and Firebase, I will be using Drupal 9, the Component module, and the TensorFlow.js module.

The loading of the data, preprocessing the data, model building and model training will be done using Colab (or Jupyter Notebook), and the model will be exported and used by Drupal to do inference using TensorFlow.js.

Read the data downloaded from [Zygmuntz's Github repository](https://github.com/zygmuntz/goodbooks-10k) After downloading these csv files, you must upload them to Colab in a directory called book-data.  They will be removed when you stop or restart the kernel.

The Book Recommender can also be viewed at [Book Recommender](https://www.drupalml.com/book-recommender).

Slide deck from presentation can be viewed at [Slide Deck](https://www.beautiful.ai/player/-MekNrs43B9td0rIkT8H).
