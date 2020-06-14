# -DL2020-NN-Animal-clasification

## To execute our code you need to put the dataset in a specific way,with this division of folders:

root/ipynb

root/data

root/data/models → (.pth.tar files  (really a pickle file .pkl) for test)

root/data/train/ → one folder per animal with his photos

root/data/validation → one folder per animal with his photos

root/data/test/test → all the image files for test

root/submissions → output of csv


## To do different tests we have touched these variables


archs = ["resnet101"]

#archs = ["vgg11"]

#pretrainedModel=False

pretrainedModel=True

epochs = 10

batch_size = 128


You need to change for your url with all files for our proyect execution

drive.mount('/gdrive')

%cd /gdrive/Shared drives/DANI IVAN EDGAR MARÇAL/DEEPLEARNING/Edgar - Dani/Deep_Learning2020/final/try2


link to our models files:

https://drive.google.com/file/d/1BRUZNHSBbp9JOEokUs7M7mWsomCxA-Pn/view?usp=sharing
https://drive.google.com/file/d/1-1ayVP2tenXxLtx13FRsJm3QXv9et9r3/view?usp=sharing



## to check the results we look at the csv entries together with the test images,the correct entries are:


from 1 to 137 + 698, 699, 700 are squirrels

from 138 to 277 are horses

from 278 to 417 are elephants

from 418 to 557 are butterflies

from 558 to 697 are sheep

