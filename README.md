# Motion Sensor Detection

A Python-based application that detects motion using computer vision techniques. This project utilizes OpenCV to capture video frames and identify movement within the frame.

## Features

- **Real-Time Motion Detection**: Continuously monitors video feed to detect motion.
- **Adjustable Sensitivity**: Allows users to set the sensitivity level for motion detection.
- **Logging**: Records timestamps of detected motions for analysis.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV
  - NumPy

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Pranavs1131/Motion-Sensor-Detection.git
   cd Motion-Sensor-Detection
Set Up a Virtual Environment (optional but recommended):

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Note: If a requirements.txt file is not present, you can install the necessary libraries individually:

bash
Copy
Edit
pip install opencv-python numpy
Usage
Run the Application:

bash
Copy
Edit
python motion_detector.py
Note: Replace motion_detector.py with the actual script name if different.

Adjust Sensitivity:

Modify the sensitivity settings within the script to suit your environment.
Monitor Output:

The application will display the video feed with motion detection highlights.
Detected motions' timestamps will be logged for further analysis.
Contributing
Contributions are welcome! To contribute:

Fork the repository.

Create a new branch:

bash
Copy
Edit
git checkout -b feature/your-feature-name
Make your changes and commit them:

bash
Copy
Edit
git commit -am 'Add new feature'
Push to the branch:

bash
Copy
Edit
git push origin feature/your-feature-name
Open a pull request.
