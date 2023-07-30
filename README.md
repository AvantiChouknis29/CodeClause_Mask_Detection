Face Mask Detection using OpenCV and TensorFlow
This project is a simple face mask detection application using OpenCV and TensorFlow in Python. It utilizes a pre-trained deep learning model (MobileNetV2) to classify whether a person in an image or video frame is wearing a face mask or not. The Haar Cascade classifier is used for face detection, and the model is loaded from a saved h5 file. The application annotates the detected faces with rectangles and labels indicating whether they are wearing masks or not.
Important Notes:

If you plan to use this code with a live video feed, you need to continuously capture frames from the video feed, process each frame using the face_mask_detector function, and then display the result.

The haarcascade_frontalface_alt2.xml file is a pre-trained Haar Cascade classifier for face detection. Ensure that the file is available in the same directory as the code.

The mask_recog.h5 file is the pre-trained face mask recognition model obtained from a reliable source or trained using appropriate data. Make sure it is also present in the same directory as the code.

For better results, consider using a high-quality face mask dataset to train the face mask recognition model. Ensure the dataset has a diverse range of people with and without masks.

This implementation may have limitations in real-world scenarios and might not be suitable for critical applications. Consider additional testing and fine-tuning if required.

Always remember that face mask detection is only a supportive measure and should not be used as the sole mechanism to ensure mask compliance. Always follow the guidelines provided by health authorities and organizations for proper mask-wearing and other safety measures.
