Face Verification:

REQUIREMENTS

1.Need GPU to process ML Model -- the stronger the better

2.Need Camera to take photos of yourself for positives,anchor, and verification folder

3.Installing pip dependences are optional on google colab since already included by default

4.Make a "data" and "application_data" folder

5.In "data" add folder postives, negatives, and anchor

6.In "application_data" folder add verification_images (copy photos of yourself into), faces (random negatives photos and photos of yourself to check if model can accuracy identify you), input_image (where photos go for analysis after model created)

7.For negatives folder get zip from http://vis-www.cs.umass.edu/lfw/lfw.tgz these are about 13233 photos of faces in 250x250x3

8.For anchor and positives take photos using first camera script below.

9.Change EPOCH number if need 300 works well but depends on how much data you use

10.Train model then save it to be used later

11.Have fun!!!
