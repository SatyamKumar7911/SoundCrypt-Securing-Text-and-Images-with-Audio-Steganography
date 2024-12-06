#SoundCrypt: Securing Text and Images with Audio Steganography


SoundCrypt is an innovative open-source project designed to enhance the security of sensitive information by embedding it into audio files. Leveraging advanced steganographic techniques and cryptographic methods, SoundCrypt provides a robust solution for hiding and extracting messages within various media formats. This project is an excellent opportunity for developers and enthusiasts to contribute to a meaningful tool, enhancing its usability and functionality.

Overview
SoundCrypt facilitates secure data hiding and extraction in images and wave audio files, ensuring that sensitive information remains concealed. This project integrates encryption with steganography, offering an added layer of security for the hidden content. The program supports a graphical user interface (GUI) for intuitive interaction and is built with Python, using libraries like Pillow, PyCryptoDome, NumPy, and PyAudio for efficient operations.

Key Features
Image Steganography: Hide and retrieve secret messages from images by modifying the least significant bits (LSBs) of pixel values.

Wave Audio Steganography: Embed and extract messages from audio files by altering the LSBs of audio frames.

Cryptographic Security: Enhance protection through the use of encryption algorithms.

User-Friendly GUI: Simplify the process with an interactive graphical interface.

Project Structure
Image Steganography:

Encode Class: Handles encoding (hiding) secret messages within images.

Decode Class: Manages decoding (extracting) secret messages from images.

Wave Audio Steganography:

ExtractWaveGUI Class: Provides a GUI for extracting messages from wave audio files.

HiddenWaveGUI Class: Offers a GUI for embedding messages into wave audio files.
