OpenCV OpticalFlow Showcase
===========================

## About
This is sample code for trying methods of computer vision called [Optical Flow](https://en.wikipedia.org/wiki/Optical_flow) casually with [OpenCV](http://opencv.org).

This is better version of 'samples/python2/opt_flow.py' included in OpenCV.
Features:
- Switchable to 4 type of optical flow methods.
- Not accumulating 'flow' for easy understanding. 
- Flipping video image horizontally for easy understanding.
- Summarized code for each methods.

## Example

- Gunnar-Farneback method: By HSV
![HSV](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/hsv.png "HSV") ![HSV SRC](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/hsv_src.png "HSV Source")

- Gunnar-Farneback method: By lines
![LINES](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/lines.png "LINES") ![LINES SRC](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/lines_src.png "LINES Source")

- Gunnar-Farneback method: By warping
![WARP](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/warp.png "WARP") ![WARP SRC](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/warp_src.png "WARP Source")

- Lucas-Kande method
![Lucas-Kande](https://github.com/daisukelab/cv_opt_flow/blob/master/sample_result/lk.png "Lucas-Kande")

## Tested Environment
MacOS X El Capitan
python 2.7.10
OpenCV3 3.1.0

## Running this sample
Simply run main.py.

       $ python main.py

       Hit followings to switch to:
       1 - Dense optical flow by HSV color image (default);
       2 - Dense optical flow by lines;
       3 - Dense optical flow by warped image;
       4 - Lucas-Kande method.

       Hit 's' to save image.

       Hit ESC to exit.

* Click on the preview window to enter commands.

## About code
| file | description |
|------|-------------|
|main.py|Main to run this sample.|
|OpticalFlowShowcase.py|Optical flow sample body.|

OpticalFlowShowcase.py has following classes.

![Class diagram](https://github.com/daisukelab/cv_opt_flow/blob/master/classOFS.png "Class diagram")
