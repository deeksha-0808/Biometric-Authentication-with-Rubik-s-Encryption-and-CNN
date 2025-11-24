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
