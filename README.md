# Driver-Drowsiness

Motivation-
Driver drowsiness help to reduce the chances of accidents caused ue to sleep while driving.

Tools used-
opencv.

Libraries used-
dlib,face-recognition

Methadology followed-

We detect the position of eyes using the euclidian distance in the shape_predictor_68_face_landmarks.dat dataset and then find the eye ratio by taking mean of the left and right eye. If the ratio is less than 0.25 than by using pyttsx3 we use the sound which alert us.

