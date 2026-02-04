# Software installation

## System Requirements

* Operating System: Ubuntu 22.04
* NVIDIA GPU

## Prerequisites

Since VisionPilot requires AI packages, we need to install the following packages first.

* **CUDA**: Optional for GPU processing.
* **OpenCV**: For image and video processing.
    * Ubuntu: `sudo apt install libopencv-dev`
* **ONNX Runtime**: For model inference.
    * Download from [the GitHub release](https://github.com/microsoft/onnxruntime/releases)
* **LibTorch**: For tensor manipulation capabilities.
    * Download from [the PyTorch website](https://pytorch.org/get-started/locally/)
* **TensorRT**: Improve the inference performance.
    * Download from [the website](https://developer.nvidia.com/tensorrt)
    * Follow [the tutorial](https://docs.nvidia.com/deeplearning/tensorrt/latest/installing-tensorrt/installing.html) to install.

## Get the code & data

* Download the code

```bash
git clone https://github.com/autowarefoundation/autoware.privately-owned-vehicles.git
cd autoware.privately-owned-vehicles/VisionPilot
```

* Download the video: You can download any dashcam video on YouTube

```bash
# Create a folder for the video and models
mkdir -p data
cd data
# Put your video here, and name it as video.mp4
```

* Download the models

```bash
# Tool to download from Google Drive
pipx install gdown
# SceneSeg
gdown -O models/ 'https://docs.google.com/uc?export=download&id=1l-dniunvYyFKvLD7k16Png3AsVTuMl9f'
# Scene3D
gdown -O models/ 'https://docs.google.com/uc?export=download&id=19gMPt_1z4eujo4jm5XKuH-8eafh-wJC6'
# DomainSeg
gdown -O models/ 'https://docs.google.com/uc?export=download&id=1zCworKw4aQ9_hDBkHfj1-sXitAAebl5Y'
```
