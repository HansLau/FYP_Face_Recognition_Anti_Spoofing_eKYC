Aritificial Intellgence (AI) based e-KYC system that reads an ID card, and then performs facial recognition and liveness detection in order to prevent identity-spoofing. Results are used to further train recognition model and for better performance and accuracy.
GUI is provided using Streamlit. MediaPipe's DeepFace module for face verification. 

Input using webcam or video files are provided.

![image](https://github.com/HansLau/FYP_Face_Recognition_Anti_Spoofing_eKYC/assets/37809287/e30d5240-d417-47c6-bf13-5dc6ba0749f4)
![image](https://github.com/HansLau/FYP_Face_Recognition_Anti_Spoofing_eKYC/assets/37809287/55cd360a-28c8-43ac-a59d-8b3ccc241921)


The system performs the following steps for verifying the user's face and the face on the ID card, and performing a liveness detection.
1. To crop and perform perspective correction on an ID card from an image.
2. To perform OCR on text on the ID to compare and verify user details provided.
3. To perform facial recognition and comparison between the face image on the ID and the real user’s facial features.
4. To perform liveliness detection on user using a camera to ensure the person is not imitating or impersonating another person.
6. To allow users an easy hassle-free experience in performing e-KYC verification
7. To accurately name user facial data to user details based on information from their identity cards using OCR

![image](https://github.com/HansLau/FYP_Face_Recognition_Anti_Spoofing_eKYC/assets/37809287/885b65e1-8a3f-4f7a-a325-291ce11d69c7)
