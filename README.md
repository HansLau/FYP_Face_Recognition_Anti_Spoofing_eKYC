Functional e-KYC system that firstly detects and reads an ID card, and then performs facial recognition and liveness detection in order to prevent identity-spoofing. Results are gathered and will be used to further train recognition model and to better integrate different components to ensure better performance and accuracy.
GUI is provided using Streamlit. 



The system performs the following steps for verifying the user's face and the face on the ID card, and performing a liveness detection.
1. To crop and perform perspective correction on an ID card from an image.
2. To perform OCR on text on the ID to compare and verify user details provided.
3. To perform facial recognition and comparison between the face image on the ID and the real user’s facial features.
4. To perform liveliness detection on user using a camera to ensure the person is not imitating or impersonating another person.
6. To allow users an easy hassle-free experience in performing e-KYC verification
7. To accurately name user facial data to user details based on information from their identity cards using OCR
