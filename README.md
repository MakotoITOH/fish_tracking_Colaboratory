This is a code for a baseline program for the FishTrackingChallenge2024 (https://ftc-2024.github.io/). 

The code is based on https://github.com/MakotoITOH/fish_tracking_ultralytics to use a fine-tuned detection model (YOLOv8 with sweetfish images) and a tracking (ByteTrack) model. 

# to use it for FishTrackingChallenge2024 

[challenge_FTC2024.ipynb](https://colab.research.google.com/github/MakotoITOH/fish_tracking_Colaboratory/blob/main/challenge_FTC2024.ipynb)

FishTrackingChallenge2024 participants can use this program to track two videos (development.mp4 and test.mp4) as a baseline.    
By default, development.mp4 can be analysed.  
If you want to analyse test.mp4, replace the line for specifying the file with the instructions in the comments before running the program.

# to use it for your own video

[fishtracking_by_uploading_video_in_colab.ipynb](https://colab.research.google.com/github/MakotoITOH/fish_tracking_Colaboratory/blob/main/fishtracking_by_uploading_video_in_colab.ipynb)

if you have your own fish videos for your use, you can use this because it contains fine-tune models of fish. 
You can upload your own videos to a specific section of the google colaboratory and track the video.  
Please bear in mind that it may take some time to upload.  
You have the option of utilizing "gdown" that can greatly decrease the uploading time.  
The example code has been included in the notes so you can customize it to match your video.

# to fine-tune the YOLOv8 model
see https://github.com/huqingrui/ultralytics_fish_tracking

# Reference
https://github.com/ultralytics/ultralytics
