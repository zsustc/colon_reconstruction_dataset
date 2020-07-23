# colon_reconstruction_dataset
this repository contains brief introdcution of simulated data for colon 3D reconstruction and the dataset download link

This dataset contains 15 cases of simulated stereo colonoscopic images with ground truth of camera poses (left camera poses, right camera poses and rotations).

In each folder named Case#, its subfolder "left" contains the left camera images and "right" contains the right camera images.
And three "txt" for mat files are left camera poses, right camera poses and rotations, the optical center of the first frame camera is used as the origin point of the global space.

Camera calibration parameters:
fx = 232.5044678; % unit in pixel
fy = 232.5044678;
cx = 240.0;
cy = 320.0;
baseline = 4.5; %unit in milimeter

datasetlink:
https://studentutsedu-my.sharepoint.com/:f:/g/personal/13026366_student_uts_edu_au/EgYXJSm-4HdEj7ZnO6S1eSUBuS0wDmjRAJpbx30VOgJhjQ?e=Bsf9rj
