📌 Overview

HideStream is a Python-based desktop application that enables users to securely hide secret messages inside text, image, audio, and video files using steganography combined with AES encryption.

Unlike traditional encryption tools that only encrypt data, HideStream conceals the existence of the message itself, adding an extra layer of privacy and protection.

This tool is designed for secure communication, privacy-focused messaging, and sensitive data protection.

1.🚀 Key Features

2.🔐 AES Symmetric Encryption (password-based security)

3.🖼️ Image Steganography (PNG, JPG)

4.🔊 Audio Steganography (WAV)

5.🎥 Video Steganography (AVI, MP4)

6.📄 Text File Data Hiding

7.🖥️ Simple & User-Friendly Tkinter GUI

8.🔄 Encode and Decode functionality

9.⚠️ Error handling for incorrect passwords & unsupported formats

🛠️ Technologies Used

1.Python

2.Tkinter – GUI development

3.PyCryptodome – AES encryption

4.NumPy – Data processing

5.Wave – Audio processing

6.OpenCV – Image & video processing

PROJECT STRUCTURE

hide_stream/
│
├── HideStream.py       # Main Tkinter application
├── audio.wav           # Sample input audio file
├── audio_out.wav       # Output audio file
├── image.jpg           # Sample input image file
├── image_out.png       # Output image file
├── text.txt            # Sample input text file
├── text_out.txt        # Output text file
├── video.avi           # Sample input video file
├── video_out.avi       # Output video file

⚙️ How It Works (Workflow)

1.User selects a supported file (text/image/audio/video)

2.User enters secret message and password

3.AES encrypts the message

4.Encrypted message is embedded inside the selected media file

5.During decoding, password is verified

6.Original message is securely recovered

▶️ How to Run the Application
1️⃣ Clone the repository
git clone <your-repository-link>

2️⃣ Install dependencies
pip install pycryptodome numpy opencv-python

3️⃣ Run the application
python HideStream.py

🎯 Use Cases

1.Secure private communication

2.Confidential information sharing

3.Digital privacy protection

4.Academic cybersecurity demonstration

5.Data hiding research projects

📊 Results

HideStream successfully hides and retrieves encrypted messages across multiple media formats while maintaining file usability and integrity.

The system demonstrates secure multimedia steganography combined with strong encryption for enhanced privacy.
