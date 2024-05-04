## Rock Paper Scissor

This is the code for Rock Paper Scissor Model for DH307 project(TinyML for digital diagnostics)

ESP32s3 was used for this project.

### Project Description: 
This was a classifcation task in which the hand postures of rock paper and scissor were to be classified using Machine learning techniques.
Dataset: https://drive.google.com/drive/folders/1z1uTTNNGiAmV2YIfWYE8uMAcPTbg4H_A?usp=sharing

MobileNetV2 was used for this project


Setup Instructions
Install ESP IDF:  https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/windows-setup.html

After you install ESP IDF in your device, so the following

1. Open ESP-IDF powershell
2. Write the following commands
   i. idf.py set-target esp32s3
   ii. idf.py build
   iii. idf.py flash monitor
