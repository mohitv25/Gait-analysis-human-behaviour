# Gait Analysis for Human Behaviour
A real-time gait-based human identification system using Computer Vision and Machine Learning.

---

## 🚀 Features
- Real-time video capture using webcam
- Silhouette extraction and GEI generation
- SVM-based person recognition
- PyQt5 GUI for registration and live inference
- Custom dataset collection

  
## Libraries to be Downloaded

To run this project, you need the following Python libraries:

- OpenCV (pip install opencv-python)
- Pillow (PIL) (pip install Pillow)
- PyQt5 (pip install PyQt5)
- NumPy (pip install numpy)
- scikit-learn (pip install scikit-learn)
- os (built-in)
- sys (built-in)
  
## Implementation
Use the application interface to register and recognize individuals based on their gait patterns.

- **Register**: Click to initiate the registration process for a new individual and write the name of the individual.
- **Save**: Click to start saving the Gait Energy Image for the current individual.
- **Recognize**: Click to begin the recognition process to identify registered individuals.
- **Update BG**: Click to update the background frame for motion detection.
## Note
- Create a folder named "gei" in the working directory for storing the "Gait Energy Images."
- Save the xml file with ".ui" extension in the working directory.
- Ensure that the ui file name is accurately specified in the src.

 ## 📸 Screenshots

### Initialization
![Initialization](assets/Initialization.jpg)

### Registration
![Registration](assets/Registration.jpg)

### Recognition / Output
![Recognition](assets/Recognition.jpg)


