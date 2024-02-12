# Facial-Recognization-System
The project "Object and Facial Detection Using AI Models" focuses on developing a sophisticated system for real-time detection of objects and faces using advanced artificial intelligence (AI) models. Leveraging cutting-edge machine learning algorithms, the project aims to create a robust and accurate solution capable of identifying various objects and faces with high precision and speed.

# System Requirements
 - OS: Windows 10 or higher
 - PROCESSOR: AMD Ryzen 5000 Series or higher
 - RAM: 8GB or higher
 - Tools: Command prompt, Vscode

# Step by step process
 - Create a directory and navigate to it
   - First, open command prompt on your windows system. Create a new directory using command

            mkdir project name
     
   - Then, Navigate to the newly created directory using command
   
            cd project name


 - Install Python
    - Next, you need to install any version (3.7, 3.8, 3.9) of Python. You can download the installer for any version from the official Python website and follow the installation instruction.
    - In this project we have used 3.9 Python version.


 - Create a virtual environment
    - Once Python is installed, Create a virtual environment namely "Myenv" using the following command
  
          python -m venv myenv

      

 - Activate the  virtual environment
    - Activate the virtual environment 'myenv" with following command

           myenv\Scripts\activate


 - Install Dependencies
    - Install the required dependencies from ImageAI, Including the numpy, pillow, Opencv-python, Torch, torchvision and torch audio. You can install them using pip command
       - Install Numpy, Pillow, matplotlib and Opencv-Python using following command

             pip install numpy pillow opencv-python matplotlib

       - Install Torch, Torchvision, torchaudio using following command

             pip install torch==1.10.0 torchvision==0.11.1 torchaudio==0.10.0


 - Install ImageAI
    - After installing necessary dependecies..,
    - Next, install ImageAI version 3.0.2 using the following pip command

           pip install imageai==3.0.2


 - Download Pre-tarined deep learning models
    - Download the Pre-trained deep learning models required for image-object detection.
       - RetinaNet Model: retinanet_resnet50_fpn_coco-eeach38b
       - YOLOv3 Model: yolov3
       - TinyYOLOv3 Mode: tiny-yolov3
           -  In this Project, We have used RetinaNet Model for image-object detection.

 - Organize Files
    - Ensure all files are saved in the same directory.

 - Run Image-object Detection Code
    - Execute the provided code for image-object detection.Make sure to have a clear, non-blurry image saved in the same directory using the following command in command prompt.
  
            python codefilename.py

 - Output
 -  - The output image will be generated in the same folder.
    - Ensure all files are stored in the same path for seamless execution of the project.
