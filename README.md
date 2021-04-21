# Image-Caption-Generator
Use combination of CNN and RNN to generate a caption from the image.
Image caption Generator is a popular research area of Artificial Intelligence that deals with image understanding and a language description for that image. Generating well-formed sentences requires both syntactic and semantic understanding of the language.

## Dataset

I have used [Flickr8k](https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb) dataset from Kaggle. It consists around 8000 images.

## What I did !!!

- Converted image to tensor and captions to tokens.
- Used **Inception_v3** to train images and LSTM to train corresponding captions.
- At last I used the output from **CNN** as input for **RNN** in our model.

## Sample Output

Image :

![Capture](https://user-images.githubusercontent.com/50714723/115616138-75baa280-a30d-11eb-8deb-88eb2f013f6b.JPG)

Output :

![Capture](https://user-images.githubusercontent.com/50714723/115616360-bc100180-a30d-11eb-9ced-fc372e9d30a9.JPG)
