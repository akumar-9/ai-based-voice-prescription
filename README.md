# AI-Based Voice Prescription

This repository contains an AI-powered application that generates medical prescriptions using speech recognition. The generated prescription can be saved as a PDF and shared via email.

## Features
- **Speech Recognition**: Fill patient details using voice commands.
- **Dynamic Prescription Generation**: Customize prescriptions with patient data, symptoms, diagnosis, and medication.
- **Save as PDF**: Generate a prescription and save it as a PDF.
- **Email Integration**: Share prescriptions directly via email.
- **Interactive GUI**: User-friendly interface built with Tkinter.

## Prerequisites
- Python 3.8 or later
- Libraries:
  - `cv2` (OpenCV)
  - `Pillow`
  - `speech_recognition`
  - `pyttsx3`
  - `smtplib`
  - `tkinter`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/akumar-9/ai-based-voice-prescription.git
   cd ai-based-voice-prescription
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the `prescription-template.jpg` is placed in the `template` folder.

## Usage

1. Run the application:
   ```bash
   python main.py
   ```

2. Use the GUI to:
   - Add patient details using voice or manual input.
   - Add medications and other details.
   - Save the prescription as a PDF.
   - Share the prescription via email.

## File Structure

```
|-- main.py                  # Main GUI application
|-- prescription.py          # Logic for generating prescriptions
|-- template/                # Template folder containing prescription image
|   |-- prescription-template.jpg
|-- ICON vp.ico              # Icon for the application
|-- README.md                # Project documentation
```

## Key Functionalities

### Voice Commands
- Fill patient details such as name, age, gender, symptoms, diagnosis, and medications.
- Use speech-to-text to dynamically populate fields in the prescription.

### Prescription Generation
- Automatically populate fields on a pre-designed template.
- Save the prescription in PDF format.

### Email Sharing
- Attach the generated prescription and send it to a specified email address using SMTP.

## Dependencies
Install the dependencies listed below before running the application:

```bash
pip install opencv-python pillow speechrecognition pyttsx3
```

## License
This project is licensed under the [MIT License](LICENSE).

## About
- **Developed By**: Akshay Kumar and Abhishek Negi.
- **Description**: This application provides a seamless way to generate and share medical prescriptions using AI and voice commands.
