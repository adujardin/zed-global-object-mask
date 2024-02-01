# ZED Global Object Mask

ZED SDK sample to get a single mask from the detected objects or bodies.

The sample is based on concurrent Object detection and body tracking implementation in C++. The function that creates the mask are in the main file (`createGlobalMaskFromObjectsMask` and `createGlobalMaskFromBodiesMask`). It currently output float matrix with the tracking id as pixel value. It can also output the bounding box rectangle in the same way.
