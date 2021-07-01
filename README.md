# Drowsiness_Detector

I have made drowsiness detector using CNN and openCV, first we train CNN and then use this saved CNN model in drowsiness_detection.py, where we use openCV to capture our face from webcam and if closed eye is detected(predicted by CNN) by the model, the model increase the count and whenever the count passes a threshold value then the alarm start buzzing.
