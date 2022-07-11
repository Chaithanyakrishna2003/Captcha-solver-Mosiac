# Captcha-solver-Mosiac
This Repository contains a machine learning model, that can be used to detect individual letters and emojis out of a given image of Captcha.

The Repository has the following files:

An image segmentor file, that basically cleans up the image, and makes contours around every individual character/emoji to segregate it as a different entity.

A machine learning model, that uses Convolutional Neural Networks to identify the contoured character.

A character set, containing sample images of each character that could appear in the captcha.
