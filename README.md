This repository is a basic image classification used for the PotPy app.
~~It uses Tensorflow Lite because we are not trying to overcharge our Raspberry Pi here. And we find
it easier and faster to use a **pre-trained model**.~~ 
Actually, why not learn something new ? Well , I am finally using PyTorch y'all -_excitement tears_. 
## Things I've learnt by working on this project 
### Scrapping from Google Images
_who knew ?_ Why have I never thought of this? 
Anyway, I've learnt that [on quora](https://www.quora.com/How-can-I-download-all-images-from-Google-image-search-engine-at-once). The first answer is the one. If you don't mind downloading new packages, 
you can also use [THIS](https://medium.com/@intprogrammer/how-to-scrape-google-for-images-to-train-your-machine-learning-classifiers-on-565076972ce). I find that one easier for Linux users. Honestly, we didn't use too many images
so we just need the download step. If there's any unwanted image, I just delete it -_-
### PyTorch 
Here is where I learnt that : [on their official website](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)

Note: files that are not shown in this repository are the pictures used for training the model. I guess you understood that I built these folders using the method 
I talked about above. The pictures are put into different folders, each of the folders have the appropriate name of the pictures inside of it. All of the folders are in the data folder. 

