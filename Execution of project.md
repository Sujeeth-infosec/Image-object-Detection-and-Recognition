# Index
 - About Image object Detection and Recognition
    - Key components
      
 - Requirements
    - System Requirements
    - Tools used
      
 - Make a Directory
    - Create a new directory
      
 - Create and Activate an Environment
    - Create an new Enviroment
    - Configure an Environment
   
 - Download Packages and dependencies
    - Download Packages
    - Download Dependencies
    - Configure Packages and Dependencies
  
      
 - Install ImageAI
    - Download ImageAI Model
    - Configure the models
 
 - Download and integrate Pre-Trained Deep learning models
 - Implement and run an code
 - Output
 - Documentation

# About the Image object Detection and Recognition
 - The project Image-Object Detection and Recognition represent a crucial area of computer vision and artificial intelligence, aimed at identifying and categorizing both human faces and other objects within images or videos. This interdisciplinary field integrates advanced algorithms and models to achieve high accuracy and efficiency in detecting faces and objects, attributing to various applications such as surveillance, security, augmented reality, and human-computer interaction.

 # Key Components:

 - Detection
    - The process involves identifying and locating faces and objects within a given image or video frame. Advanced techniques like convolutional neural networks (CNNs) and deep learning architectures are commonly employed for precise detection.
 - Recognition
    - Following detection, recognition algorithms are applied to identify and classify the detected faces and objects. Facial recognition systems utilize features like facial landmarks, patterns, and biometric characteristics for accurate identification.
 - Feature Extraction
    -  Extracting relevant features from detected faces and objects is essential for subsequent recognition tasks. Feature extraction methods include traditional techniques like Haar cascades and modern approaches like feature pyramid networks.
Training and Optimization
    - Machine learning models are trained and optimized using labeled datasets to improve detection and recognition accuracy. Techniques such as data augmentation, transfer learning, and fine-tuning are employed to enhance model performance.
 - Real-time Implementation
    - Deploying detection and recognition systems in real-time scenarios requires efficient algorithms and optimization for rapid processing of input streams. Hardware acceleration and parallel processing techniques are often utilized to achieve real-time performance.
 - Applications:
    - Facial-Object Detection and Recognition find diverse applications across various domains, including security and surveillance systems for identifying individuals and suspicious activities, interactive interfaces for gaming and virtual reality, and autonomous vehicles for object detection and obstacle avoidance.
Overall, Facial-Object Detection and Recognition play a pivotal role in advancing technology-driven solutions for complex visual perception tasks, with continuous advancements contributing to improved accuracy, speed, and reliability in identifying both faces and objects in diverse environments.

# Install Python Software

 - Install a python from official site
   

 - Select Python version 3.9.2 for windows


# System requirements
 - OS: Windows 10
 - PROCESSOR: AMD Ryzen 5 5625U
 - RAM: 8GB
 - Tools we used for project
    -  Command prompt - to integrate the pre-trained models with real-time images & objects 
    -  VScode - for path edits and coding

# Create new Directory
 - Create a directory and navigate to directory using following commands

         mkdir project

   ![mkdir project](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/f3e9e58e-6ceb-4127-b5df-3aa3526ea278)

   ![project directory](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/bd316f3c-b6d3-45c0-bfa1-50bc5747ff28)

 


 -  This command navigate to the directory destination we specified in command

         cd project



  ![mkdir project](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/a12391d8-eb2d-47b4-88be-7e4fd31063d2)


# Create a new environment
 - create new environment for project in same created directory by using following command

        Python -m venv myenv
  
![python -m venv myenv](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/86354b2e-5730-477d-b42a-70ea6a6a1994)

 ![myenv](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/4396324c-1b3c-47c1-ba51-9746658461d6)

![env file](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/73965ab3-40c3-4252-8f0d-1506b84be6c0)


 - Now Activate the Environment using the following command to accept the changes of pip, installations of files, dependencies in environment level

       myenv\Scripts\activate

   ![activate](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/c4067475-0dfa-4a79-ae34-3bd428619228)

# Download packages & dependencies 
 - Navigate to the directory and install the packages and dependencies by using the following commands mentioned below.
 - In this project we use few packages
    - OpenCv-Python
    - Numpy
    - Pillow
    - matplotlib
    - torch==1.10.1
    - torchvision==0.11.1
    - torchaudio==0.10.0

          pip install numpy pillow opencv-python matplotlib

![numpy pillow](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/394116de-51f6-4385-95f8-ee7e981052b4)


       pip install torch==1.10.1 torchvision==0.11.1 torchaudio==0.10.0


  ![torch vision](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/75ac3d18-5652-458a-8d2b-4088ba33866d)

# Install ImageAI
 - After installing packages in previous steps, we need to install an package named "imageai" by using the following command in command prompt

        pip install imageai==3.0.2

   ![imageai](https://github.com/Sujeeth-infosec/Image-object-Detection-and-Recognition/assets/56471468/b59913d4-2f8f-4487-8436-60ab71f1dd77)


# Download an pre-trained Pre-Trained Deep learning models
 - Deep-learning
 - download the pre-trained model into the path directory "Project" as mentioned below  
