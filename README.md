# Overview:
A machine learning starter project for processing the data from bulgarian id card (the old id-card standard) images to a machine readable list of strings format. The project utilises 3 instance segmentation models trained beforehand with the Detectron2 (https://github.com/facebookresearch/detectron2) open source library. Another key component is the Pytesseract library which serves as a wrapper for the Tesseract-OCR (https://github.com/tesseract-ocr/tesseract) library. The project serves as a foundation for further development in the fields of computer vision and automatisation of processes.


# Installation Guide:
In order to run the project, a few libraries and tools have to be installed in a particular order to set up the required environment for the program. Once the environment is set up, run the app-flask.py file and a simple user interface will start on the http address http://127.0.0.1:5000 where you can use the program.

The following installation steps are provided using pip, the recommended package manager for Python. These instructions assume you are working in a Python environment where pip is available. However, if you prefer or need to use a different package manager (e.g., conda for Anaconda environments, apt-get for Debian-based systems, or brew for macOS), you are welcome to adapt the commands accordingly based on your operating system and environment.
```
* pip install torch
* pip install flask
* pip install imutils
* pip install tesseract
* pip install fvcore
* pip install pycocotools
* pip install cloudpickle
* pip install omegaconf

* Install Microsoft Visual Studio with the "Desktop development with C++" workload. Official MVS website download page: https://visualstudio.microsoft.com/downloads/
* Include the  the individual components "MSVC v142 - VS 2019 c++ x64/x86 build tools (v14.27)" and "MSVC v142 - VS 2019 c++ x64/x86 spectre-mitigated libs (v14.27)" in the installation

* Install Tesseract-OCR by following the official installation guide here: https://github.com/UB-Mannheim/tesseract/wiki
* Download the bul.traineddata file from https://github.com/tesseract-ocr/tessdata and add it in you the directory of your Tesseract installation in the "tessdata" folder.

* pip install pytesseract
```

# Technologies:
* Detectron2
* Pytesseract + Tesseract-OCR
* Python Flask web framework
