# SIP-2023---AAI07
Project Objective: Improve the performance of an AI object detection model through fusing bounding boxes produced by the machine with human predictions
- Assumption: Humans will make different mistakes from the ML model
- Application: improve machine learning predictions for object detection in self-driving cars

Project Description: Combining the human-produced bounding boxes with the YOLO-NAS model predictions to improve overall performance using Weighted Box
Fusion (WBF) and Soft Non-Maximum Suppression (NMS)
- WBF: Compare results for different methods for setting the human confidence score (fixed constants ranging from 0.4 to 1, random float between 0.5-1)

Results:
https://docs.google.com/spreadsheets/d/1MRRqeH1MWEcnwlFa1WqtdEUwDRPKKwn0YN-MoxUX9SI/edit#gid=1372991454 
