

https://github.com/VAUTPL/Number_Detection


*** pip install Scikit Learn and dependencies ***

# apt-get install python-sklearn
# apt install python3-sklearn
# pip install sklearn --upgrade
# apt-get install python-skimage
# pip2 install mahotas
# pip2 install imutils


*** Running ***

- Train model
# python train.py -d data/digits.csv -m models/svm.cpickle
- Detect the number of meters from an image file
# python detect_numbers_images.py -m models/svm.cpickle -i images/f4.jpg
- Detect the number of meters fom web cam
# python detect_numbers_webcam.py --model models/svm.cpickle
