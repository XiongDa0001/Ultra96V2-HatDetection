# Ultra96-HatDetection
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

# PS:This vedio detection exists a bug. When detecting hat object, the detection page will start flashing
