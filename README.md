# Multimodal Biometric Encryption & Steganography System
A multimodal biometric security system combining fingerprint and iris verification with RubikCube image encryption, DCT-based steganography, audio LSB encoding, and PDF watermarking. Built using Flask, it enables secure encryption, decryption, and authentication of digital media with OTP-based access control.

# 1. Biometric Authentication
Fingerprint and iris matching
Mandatory before encryption/decryption
# 2. Image Encryption (RubikCube Algorithm)
Block scrambling & permutation
Key-based secure encrypt/decrypt
# 3. DCT-Based Image Steganography
Hides data in DCT DC coefficients
Supports encode + decode
# 4. Audio Steganography (LSB Method)
Embeds secret text in WAV audio
Extracts hidden messages securely
# 5. PDF Encryption & Watermarking
Converts PDF → image → encrypted
Adds watermark for verification
Reconstructs decrypted PDF
# 6. OTP Verification
Telegram Bot API
OTP required for decryption  

# System Architecture
User Input
     ↓
Biometric Verification (Fingerprint + Iris)
     ↓
OTP Verification (Telegram Bot)
     ↓
Media Operations
     ├── Image Encryption / Decryption
     ├── Image Steganography
     ├── Audio Steganography
     └── PDF Encryption / Watermarking
     ↓
Output Files (Encrypted, Decrypted, Watermarked)

# Project Structure
project/
│
├── app.py
├── audio_steganography.py
├── image_utils.py
├── test_encrypt.py
│
├── fingerprint/
│   └── FTesting.py
│
├── iris/
│   └── ITesting.py
│
├── templates/
│   ├── home.html
│   ├── audio.html
│   └── PDF.html
│
├── static/
│   ├── original/
│   ├── encrypted/
│   ├── decrypted/
│   ├── audio/
│   ├── pdf/
│   ├── pdforiginal/
│   ├── pdfencrypted/
│   ├── pdfdecrypt/
│   └── watermarked/
│
├── requirements.txt
└── README.md

# Installation
git clone <your-repo-url>
cd project
pip install -r requirements.txt

# Run the Application
python app.py

# Technologies and Libraries
Python
Flask
OpenCV
NumPy
PyMuPDF
Pillow
RubikCubeCrypto
Matplotlib
Wave
Telepot (OTP)

# Applications
Secure digital communication
Confidential document handling
Cryptographic research
Academic and industry-grade biometric security systems

# Security Notice
Do not upload:
key.txt
Telegram bot tokens
Any private datasets
Add them to .gitignore before pushing to a public repository.

# About This Project
This system integrates biometrics, encryption, steganography, and web technologies to create a complete secure digital media pipeline. It demonstrates strong practical knowledge in computer vision, cryptography, and backend development—ideal for showcasing on resumes, GitHub portfolios, and academic publications.
