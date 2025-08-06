### Dog Breed Classification

This project aims to build an end-to-end multiclass dog breed classifier. Given an image of a dog, the model will process the image and output the predicted breed. The ultimate goal is to create a system that can identify a dog's breed instantly from a picture.

---

### Problem Definition

The problem is to classify an image of a dog into one of 120 different breeds. The model should be able to take an image as input and predict the dog's breed.

---

### Data

The dataset used for this project was obtained from a Kaggle competition: [Dog Breed Identification](https://www.kaggle.com/competitions/dog-breed-identification/data). The data consists of images (unstructured data), making deep learning and transfer learning suitable approaches.

* **Training Data**: Contains over 10,000 images with labels for 120 different breeds.
* **Test Data**: Contains over 10,000 images without labels, which are used for prediction.

---

### Evaluation

The model's performance is evaluated using **Multi Class Log Loss** between the predicted probability and the observed target. The submission format details can be found on the Kaggle competition page.

---

### Libraries

The project uses the following key libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `tensorflow`
* `tensorflow_hub`
