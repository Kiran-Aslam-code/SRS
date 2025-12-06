Blur Detection works using the total variance of the Laplacian of an image, this provides a quick and accurate method for scoring how blurry an image is. In this document, we aim to describe how machine learning approaches can be applied to detect blur in images.

Purpose
The purpose of our proposed model is to automatically detect the blurry effects in image. Since human efforts in detecting the blurry features took time when reading hundreds file in a folder, our proposed system will be capable enough to detect blurry effects in no time. 

Scope
The scope of our proposed title lies in the domain of application of machine learning algorithms in image processing.

Product Perspective
Our blur detection is based on image patches, making region-wise training and classification in one image efficient. Extensive experiments show that our method works satisfactorily on challenging image data, which establishes a technical foundation for solving several computer vision problems, such as motion analysis and image restoration, using the blur information.
The following subsections describe how the software operates inside various constraints.

User Characteristics
Edge Sharpness,Frequency Domain Analysis,Contrast & Texture,Blur Metric - Edge Density or SNR, Focus Measure, Perceptual Factors, Pixel Value Variability, Depth of Field (DOF).
Proposed Technologies
Python , OpenCV , Laplacian Operator and Anaconda
Authors have to provide a brief of functions of the project. For example, if a Hospital Management System is going to develop and Patient and Doctor module is going to implement then patient admission, appointment system and billing can be described here. Authors will write these items in the form of paragraph without providing some title.
Functional Requirements
The System must detect blur in an  input image .
The System must classify images as  sharp or blurred.
The System must extract features from images.
The System must train on labeled data sets.
The System must generate a clear decision output.

Purpose: Sign up process allows authorized users to create an account in order to access the image blur detection system.
User(s): Admin( manages users), Data Entry Operator(uploads images)
Name: Full name of the user as per official identification.
Password: Must contain at least 8 characters including uppercase ,lowercase,number,and a special character .
Address: Actual residence address which is accessible by post and other staff.
Phone: Working phone number. Must be on Whats App.
Display Picture: Latest face picture
Role selection : User selects their role ( Admin, data entry operator,Researcher)
Approval by Admin: Admin reviews submitted details and approves the account before access is granted.

User will be the member of system and able to login
Other requirements will be provided in similar way.
The System respond quickly .
The System should use minimal memory.
The System should maintain consistent accuracy on diverse images.
The System should support easy integration into imaging tools.
The System should remain stable during long term use.

Detects blurry photos so the device can alert the user or auto-retake the image. Ensures machine-vision systems only analyze clear images for defect detection.Identifies blurry frames so face/vehicle recognition uses only sharp footage.
 
