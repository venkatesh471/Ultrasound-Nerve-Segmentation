# Ultrasound-Nerve-Segmentation

 - Venkatesh
In Medical Field there are enormous facilities that has been never thought before, they done more
improvements in the field of surgery, x-rays, medicine and lot more but still people are facing difficulties or
pain in facing the treatment of ultrasound images. These ultrasound scans are very important to detect any
kind of injury of disease in human body because it used to scan the internal tissues of the body
Now, in this Case Study am going identify the nerve structures in ultrasound images of various patients which
is useful to decrease the pain of the patient after surgery and speedy recover.
# Data
This Data contains the images of Ultrasound nerves of neck of patients which are manually by the experts
identified the Brachial plexus where the patient finds pain.
The Data can be downloaded from here https://www.kaggle.com/c/ultrasound-nervesegmentation/data (https://www.kaggle.com/c/ultrasound-nerve-segmentation/data)
Files:
  - Train :1.08GB
    Contains 5635 images of 47 patients with their corresponding masks images.
  - Test :1.05GB
    Contains 5508 images which are to be segmented.
  - Train masks :2.14MB
  - Sample submission :48KB
  
# Model
The provided model is basically a convolutional auto-encoder, but with a twist - it has skip connections from encoder layers to decoder layers that are on the same "level". See picture below (note that image size and numbers of convolutional filters in this tutorial differs from the original U-Net architecture).


