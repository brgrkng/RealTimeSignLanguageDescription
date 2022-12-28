# RealTimeSignLanguageDescription
Real time sign language detection model using transfer learning.

Description:
Project is based on a tutorial video for face mask detection by Nicholas Renotte. https://youtube.com/watch?v=IOI0o3Cxv9Q&si=EnSIkaIECMiOmarE.
The same process was used except instead of a face mask, sign language was used. In the video the ground truth labels are 'mask' and 'no mask'. 
Here we use a number of different signs in ASL instead, where each label is performed infront of a camera and labeled accordingly.

'Paper.pdf' was what I submitted for my assignment for which i got an 85/100. 

You can run the program through the IPYNB by running the block under the 'Deployment' section, unfortunately this probably wont work correctly for anyone else as the dataset is small and specific to the lighting in my room and my own skin tone :( .

Dependencies (i might've missed a few): 
            Python
                glob
                pandas
                numpy
                Pillow
                tensorflow
                open-cv
                object_detection
             Protoc
             
More dependencies if you want to re-train the model yourself, fun tutorial here: https://youtube.com/watch?v=dZh_ps8gKgs&si=EnSIkaIECMiOmarE!
