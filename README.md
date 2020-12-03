# Amazing_Person_Detection
CPU Real-time Amazing Multi-scale Person Detection
# FIND CODE  
https://blog.csdn.net/samylee/article/details/103395516  
# Test steps
## step1
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/14VIsF6PD6ktU7ctUh301wA)
## step2
Set parameters:
`Amazing_Person_Detection.exe test_type img_path`
```cpp
like:  Amazing_Person_Detection.exe image test.jpg  (for image)
or:    Amazing_Person_Detection.exe imgdir /img/path/test_imgs  (for imgdir)
or:    Amazing_Person_Detection.exe video test.avi  (for video)
or:    Amazing_Person_Detection.exe video 0  (for usbcam)
```
# Algorithm efficiency
| Image Size | min_size | CPU(i7-9700K) Speed/FPS | CPU(ARMv7 @1.4GHz) Speed/FPS |
|:------:|:------:|:------:|:------:|
| 320x240  | 10x10 | 8ms/125.0 |46ms/21.7|
| 640x480  | 10x10 | 28ms/35.7 |210ms/4.8|
| 800x600  | 10x10 | 42ms/23.8 |    -    |
# Test experience
If the image size is larger than `720p`, it is recommended to scale the image `below 720p`!
# Example result
![image](https://github.com/samylee/Amazing_Person_Detection/blob/master/result.jpg)
# Reference
https://blog.csdn.net/samylee
