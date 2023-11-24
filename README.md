# ReadMe
This is a code for tracking fish that is based on the Ultralytics code found at https://github.com/ultralytics/ultralytics.  
I have made adjustments to the code found on the Github page located at https://github.com/MakotoITOH/fish_tracking_ultralytics so that it can work with Google Colaboratory.  
The code has been trained and fine-tuned to function with the experimental video being used for the FishTrackingChallenge2024.  
As such, it can be used as a baseline program for the FishTrackingChallenge2024 (https://ftc-2024.github.io/).  

# Handling instructions

## challenge_FTC2024.jpynb
### for those who want to use it for FishTrackingChallenge2024  
FishTrackingChallenge2024 participants can use this programme to track two videos(development.mp4 and test.mp4) as a baseline.    
By default, development.mp4 can be analysed.  
If you want to analyse test.mp4, replace the line for specifying the file with the instructions in the comments before running the program.

## fishtracking_by_uploading_video_in_colab.ipynb
### for those who want to use it for your own movie

It contains fine-tune models of fish, so if you have your own fish videos for your use, you can use this.
You can upload your own videos to a specific section of the google colaboratory and track it.  
Please bear in mind that it may take some time to upload.  
You have the option of utilizing "gdown" that can greatly decrease the uploading time.  
The example code has been included in the notes so you can customize it to match your video.