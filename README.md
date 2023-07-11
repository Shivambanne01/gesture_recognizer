# gesture_recognizer
Gesture recognition guide for Android (java)

The MediaPipe Gesture Recognizer task lets you recognize hand gestures in real time, and provides the recognized hand gesture results along with the landmarks of the detected hands. You can use this task to recognize specific hand gestures from a user, and invoke application features that correspond to those gestures.

This task operates on image data with a machine learning (ML) model, and accepts either static data or a continuous stream. The task outputs hand landmarks in image coordinates, hand landmarks in world coordinates, handedness (left/right hand), and the hand gesture categories of multiple hands.

Dependencies
The Gesture Recognizer task uses the com.google.mediapipe:tasks-vision library. Add this dependency to the build.gradle file of your Android app:

dependencies {
    implementation 'com.google.mediapipe:tasks-vision:latest.release'
}


