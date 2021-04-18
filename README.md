# SiameseChangeDetection
Complete Pipeline of Siamese Change detection
# Problem:
To Identify changes in video lectures using Siamese network with triplet loss function.
Frames Extraction:
For the extraction of frames, we have used OpenCV library. The Video is first converted into frames and then assign class numbers based on frame numbers given in the pickle file. After assigning the class numbers, the frames are pre-processed to resize the size and convert it into int32 format. Figure 1 shows the flowchart of the approach.
