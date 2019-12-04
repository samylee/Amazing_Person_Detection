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
| Image Size | Speed | mAP(voc2007-test) | CPU |
|:------:|:------:|:------:|:------:|
| Any resolution image  | 60ms |0.7714| i7-8750H @2.20GHz |

# Example result
![image](https://github.com/samylee/Amazing_Person_Detection/blob/master/result/0.jpg)
![image](https://github.com/samylee/Amazing_Person_Detection/blob/master/result/1.jpg)
# Reference
https://blog.csdn.net/samylee
