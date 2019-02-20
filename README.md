# Fly Recognition

This repository contains the software developed at FlySleepLab (Liu Lab) @VIB-KU Leuven CBD to power behavioral tracking in _Drosophila_ _melanogaster_.
It consists of a collection of open source software either published by other groups (like [DeepLabCut](https://github.com/AlexEMG/DeepLabCut)  or by ourselves.


## Current lines of action / TO-DOs
- [x] Try training with less labeled points i.e. one point or feature to be tracked.

Check 
[https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Fly-Sayed-2019-02-20/videos/outpy05_reshapeDeepCut_resnet50_FlyFeb20shuffle1_200_labeled.mp4](https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Fly-Sayed-2019-02-20/videos/outpy05_reshapeDeepCut_resnet50_FlyFeb20shuffle1_200_labeled.mp4) 
 to see how DLC does tracking the separator of the arena. It's a trivial task, but it works.

- [x] Label easier objects i.e. the corners of the arena, which don't change

- [x] Crop videos to focus just on the relevant ROI

Check [https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Track_flies-Sayed-2019-02-20/videos/outpy05_reshaped_topDeepCut_resnet50_Track_fliesFeb20shuffle1_200_labeled.mp4](https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Track_flies-Sayed-2019-02-20/videos/outpy05_reshaped_topDeepCut_resnet50_Track_fliesFeb20shuffle1_200_labeled.mp4) and [https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Track_flies-Sayed-2019-02-20/videos/outpy05_reshaped_bottomDeepCut_resnet50_Track_fliesFeb20shuffle1_200_labeled.mp4](https://github.com/VIBFlySleepLab/FlyRecognition/blob/master/DLC/examples/Track_flies-Sayed-2019-02-20/videos/outpy05_reshaped_bottomDeepCut_resnet50_Track_fliesFeb20shuffle1_200_labeled.mp4) to check how well DLC does after 200 iterations looking at each area separately. 
Mind that DLC was trained on a different video (outpy04.avi) i.e. it's predicting based on the frames of another video (it's however, very similar).

- [ ] Add more videos

- [ ] Start something out of DLC (by ourselves)
