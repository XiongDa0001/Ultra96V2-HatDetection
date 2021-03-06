
# Object Detection For Xilinx Summer School

In the complex construction environment, the helmet wearing detection algorithm based on machine vision technology often has missed detection and false detection, its detection ability is limited, and the available resources on the board are limited. To solve the above problems, I used the lightweight network detection framework yolov4 tiny to realize helmet wearing detection.

Please use PYNQ image and prepare pynq-dpu environment.
This project relies on vitis-ai 1.2 release.

## 1.download DPU-PYNQ 1.2.0 
  https://github.com/Xilinx/DPU-PYNQ/tree/v1.2.0
  
  cd DPU-PYNQ/upgrade
  
  make
  
## 2.install pynq-dpu
  pip3 install pynq-dpu==1.2.0
  
  cd $PYNQ_JUPYTER_NOTEBOOKS
  
  pynq get-notebooks pynq-dpu -p .
  
## 3.how to run
 ### YOLOv4-tiny.ipynb is used for image detection.
![image](https://user-images.githubusercontent.com/71107056/128302693-d71024f3-3c32-473c-81e0-27da1f640ba9.png)


 ### vedio-YOLOv4-tiny.ipynb is used for real-time detection. This project  needs a drive free camera.
![image](https://user-images.githubusercontent.com/71107056/128302856-5130d2a7-08f7-4498-8dde-58ccab1c3a09.png)


# PS:This vedio detection exists a bug. When detecting hat object, the detection page will start flashing
