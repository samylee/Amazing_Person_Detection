# Amazing_Person_Detection
CPU Real-time Amazing Multi-scale Person Detection
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
| Image Size | Speed | FPS | CPU | min_size |
|:------:|:------:|:------:|:------:|:------:|
| 320x240  | 8ms |125| i7-9700K | 10x10 |
| 640x480  | 28ms |35.7| i7-9700K | 10x10 |
| 800x600  | 42ms |23.8| i7-9700K | 10x10 |
# Test experience
If the image size is larger than `720p`, it is recommended to scale the image `below 720p`!
# Example result
![image](https://github.com/samylee/Amazing_Person_Detection/blob/master/result.jpg)
# Reference
https://blog.csdn.net/samylee
