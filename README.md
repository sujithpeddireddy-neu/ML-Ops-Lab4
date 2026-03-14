docker build -t lab1:v1 .

docker save lab1:v1 > my_image.tar

docker run lab1:v1

I have added the feature so that this version also evaluates the model on a test split and saves the accuracy to metrics.txt.
