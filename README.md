# FaceMask-Detection
1, build the configuration environment, correctly install the package in the requirements.txt, it is recommended that pytorch use the version between 1.7~1.8, here use pytorch1.8.
2, copy exp_* whole weight model folder to yolov5_3.0code/runs folder.
3, open detect.py and modify default=' ' after “--weights”, fill in the correct path of the model file used, that is, the full path of exp_*/weights/best.pt.
4、Store the images or videos to be tested in the inference/images folder.
5. Run detect.py to start the test, and it will generate the result images in the inference/output folder.
**
