# Face-Recognition-Attendence-System

A Face Recognition Attendance System with Anti-Spoofing feature is a sophisticated biometric solution designed to accurately identify and record individuals for attendance purposes while incorporating measures to prevent spoofing attempts. This system leverages facial recognition technology to automate attendance tracking, providing a secure and efficient alternative to traditional methods.

How it works?

User Enrollment: 

1. Capture facial images from the camera or image input.
2. Preprocess the images by resizing, normalizing, and extracting facial regions.
3. Implement liveness detection to distinguish between live faces and spoof attempts.
4. Extract features that indicate liveliness, such as texture analysis, motion detection, and depth estimation.
5. Use a combination of techniques, including:
                  - Texture analysis: Analyze facial textures for signs of realism.
                  - Motion detection: Check for natural facial movements.
                  - Depth analysis: Use 3D sensing or depth maps to identify the presence of a physical face.   
6. During user enrollment, capture multiple images of the user's face under various conditions to create a robust template.
7. Store the encrypted facial templates securely in a database.

Attendance Tracking:

1. Capture facial images during attendance tracking.
2. Compare the captured faces with the enrolled templates using the face recognition algorithm.
3. If the face is recognized, proceed to anti-spoofing checks.


Finally store the data in a log.txt file (Name . in time , out time)