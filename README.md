#
**<H1 align = "center">OpenCV Projects</H1>**

<!-- all project gif combined -->
<div align="center">
    <img height=30% src='Assets/OpenCV-main-video.gif'/>
</div>

## Description

**Author** : Susovan Das

**Language** : Python  

**External Module** : [OpenCV][opencv], [Numpy][numpy], [Pandas][pandas], [Pyzbar][pyzbar], [Face Recognition][face-recognition], [MediaPipe][mediapipe]

This Repository contents some projects on Computer Vision based on mainly  _OpneCV_ libary of Python.

All Projects are Listed here
* [Air Canvas](Air_Canvas/)
* [Harry Potter Cloak](Harry_Poter_Cloak/)
* [Color Detection](Color_Detection/)
* [Barcode Detection](Barcode_Detection/)
* [Face Recognition](Face_Recognition/)
* [Lips Coloring](Lips_Coloring/)
* [Face & Eye Detection using Haar Classifer](Face_Eye_Detection/)
* [Object Tracking](Object_Tracking/)
* [Shape Detection](#shape-detection)
* [Image Wrap Prespective View](#image-wrap-prespective-view)
* [Utils File](#utils-file)
* [WebCam](#webcam)

### Shape Detection
<img align='right' width=35% src='Assets/shape_detection.gif'/>

In this we are detecting the shapes of object by using OpenCV methods.

To download this file Click this --> &nbsp; &nbsp; [<img src="https://github.com/SusovanGithub/OpenCV-Projects/blob/master/Assets/.download_icon.png" width="20" height="20"/>][DownGit-shape_detection]

You can run this by simply double clicking the _image_warp_prespective.py_.  
Or you can use the Command Prompt/Terminal and go to the location of the _image_warp_prespective.py_ and type `python shape_detection.py`.

A window will came out named _Shape Detection_. There are 4 parameters _Threshold 1_, _Threshold 2_, _Min Area_, _Max Area_. To change this parameters you have to use the Track Pad, by changing this value selet the optimal value to detect the shapes of the object.

To exit press _ESC_ button.
<br>

### Image Wrap Prespective View
<img align='right' width=40% src='Assets/image_warp_perspective.gif'/>

In this we are creating a bird eye view of a object from a image.

To download this file Click this --> &nbsp; &nbsp; [<img src="https://github.com/SusovanGithub/OpenCV-Projects/blob/master/Assets/.download_icon.png" width="20" height="20"/>][DownGit-image_warp_prespective]

You can run this by simply double clicking the _image_warp_prespective.py_.  
Or you can use the Command Prompt/Terminal and go to the location of the _image_warp_prespective.py_ and type `python image_warp_prespective.py`.  
A window will came out named _Main Image_ form that select the 4 points in _Z_ pattern for which object you want the Bird Eye View.

To exit press _ESC_ button.

### Utils File

This is a _python_ file which contains some useful and important functions

|**Function Name**|**Preview**|
|---|---|
|stackImage()|<img align='right' src='Assets/stackImage.gif'/>|

To download this file Click this --> &nbsp; &nbsp; [<img src="https://github.com/SusovanGithub/OpenCV-Projects/blob/master/Assets/.download_icon.png" width="20" height="20"/>][DownGit-myUtils]

### WebCam

This is a simple _python_ program to access the webcam.

To download this file Click this --> &nbsp; &nbsp; [<img src="https://github.com/SusovanGithub/OpenCV-Projects/blob/master/Assets/.download_icon.png" width="20" height="20"/>][DownGit-WebCam]

## How to Download

To download all this projects Click this --> &nbsp; &nbsp; [<img src="https://github.com/SusovanGithub/OpenCV-Projects/blob/master/Assets/.download_icon.png" width="20" height="20"/>][DownGit-main]

## Requirements

This project requir some external modules.
* OpenCV
* Numpy
* Pandas
* Pyzbar
* Face Recognition
* MediaPipe

So use the package manager [pip](https://pypi.org/project/pip/) to install those package.

```bash
pip install opencv-contrib-python
pip install numpy
pip install pandas
pip install pyzbar
pip install face-recognition
pip install mediapipe
```

<br>
<h3 align = "center"> Show some ❤️ by starring this repository!</h3>

<!--Inner Links-->
[opencv]: https://opencv.org/

[numpy]: https://numpy.org/

[pandas]: https://pypi.org/project/pandas/

[pyzbar]: https://pypi.org/project/pyzbar

[face-recognition]: https://pypi.org/project/face-recognition/

[mediapipe]: https://mediapipe.dev/

[DownGit-main]: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SusovanGithub/OpenCV-Projects

[DownGit-image_warp_prespective]: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SusovanGithub/OpenCV-Projects/blob/master/image_warp_perspective.py

[DownGit-shape_detection]: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SusovanGithub/OpenCV-Projects/blob/master/shape_detection.py

[DownGit-myUtils]: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SusovanGithub/OpenCV-Projects/blob/master/myUtils.py

[DownGit-WebCam]: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SusovanGithub/OpenCV-Projects/blob/master/webcam.py
