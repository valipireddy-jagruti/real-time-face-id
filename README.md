Overview
This project provides a complete face recognition solution that works seamlessly in Google Colab environment.
It features real-time face detection using webcam, personalized recognition with named folders, and high-accuracy identification with confidence scoring.

working steps:
Phase 1: Setup & Preparation
Open Google Colab
Go to colab.research.google.com
Create a new notebook
Ensure you're using Google Chrome browser
Camera Access Setup
When prompted, allow camera permissions
Click the camera icon in address bar → Select "Allow"
Refresh the page if needed

Phase 2: System Installation
Run the Main Code
Copy and paste the face recognition code into a Colab cell
Execute the cell (Ctrl+Enter)
Wait for all dependencies to install
Verify Installation
Look for "✅ Libraries installed successfully!" message
Check that no error messages appear

Phase 3: Training the System
Create Person Folders
Choose "Create new person folder" option from menu
Enter the person's name (e.g., "John")
Upload multiple clear photos of that person's face
Repeat for each person you want to recognize
Train Recognition Model
Select "Train system" option
System processes all images in person folders
Wait for "✅ Training completed!" message
Face encodings are automatically saved

Phase 4: Testing & Recognition
Real-time Webcam Testing
Choose "Start real-time webcam recognition"
Allow camera access if prompted
Look directly at the camera
System shows:
Green box + Name: Recognized person
Red box + "Unknown": Unrecognized face
Confidence percentage: Recognition accuracy
Photo Capture Testing
Use "Capture photo" option
Click capture button
System processes image and shows results
Download processed images if needed

Phase 5: Usage & Maintenance
Adding New People
Go back to training phase
Create new person folder with different name
Upload new person's photos
Retrain the system
Improving Accuracy
Add more training images per person
Use clear, well-lit photos
Include different angles and expressions
Ensure faces are clearly visible

Technologies Used:
OpenCV - Computer vision processing
Haar Cascades - Face detection algorithm
LBPH Recognizer - Face recognition implementation
Matplotlib - Results visualization
Google Colab JS - Webcam integration
