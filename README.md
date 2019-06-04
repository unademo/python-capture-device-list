# Wheels: List Capture Devices for Python OpenCV on Windows
**Brief**: **OpenCV** does not have an API for listing capture devices. The sample shows how to create a Python extension to invoke DirectShow C++ APIs for enumerating capture devices.

**Origin Repo Author**: [@yushulx](https://github.com/yushulx)

**Modification in this Forking Repo**: 

- Build the origin ones into wheels ( [Python3.5 Wheel](https://github.com/unaplugin/python-capture-device-list/releases/download/Release1.0/WindowsDevices-1.0-cp35-cp35m-win_amd64.whl)  |  [Python3.6 Wheel](https://github.com/unaplugin/python-capture-device-list/releases/download/Release1.0/WindowsDevices-1.0-cp36-cp36m-win_amd64.whl) ), since the origin repo could not build successfully on Anaconda Python.

## Environment
* **Native Python** or **Anaconda Python**

* **Python environment**: 3.5 or 3.6

* **OpenCV 3.3.0** (To ```cv2.VideoCapture``` the devices)

## How to Run 
1. Download the wheel in the **[Release Page](https://github.com/unaplugin/python-capture-device-list/releases)**
    
2. Download the ```test.py``` to run & test the module **```device```**:
    ```
    python python test.py
    ```
    
    or 

    ```
    python python3 test.py
    ```   
   
## Blogs of original repo
[Listing Multiple Cameras for OpenCV-Python on Windows][1]

[0]:https://en.wikipedia.org/wiki/Microsoft_Windows_SDK
[1]:http://www.codepool.biz/multiple-camera-opencv-python-windows.html



