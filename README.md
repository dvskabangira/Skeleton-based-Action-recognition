# Skeleton-based-Action-recognition
Recognizing challenging behavioral activities from videos sequences or still images can be so challenging due
to background noise, partial occlusion, changes in scale, viewpoint, lighting and appearance. 
In this project, we use a skeleton-based hybrid approach of pose estimates and Conv3D for action recognition
The model takes in 2D poses represented by stacks of heatmaps of skeleton joints.
The heatmaps at different timesteps are stacked along temporal dimensions to form 3D  heatmaps which are fed into 3D-CNN for challenging action recognition

------
***Results***
