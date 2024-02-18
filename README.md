# Varifocal Display Systems for VR
<img src="images/UW Reality Labs Icon.png" width="150" height="150" alt="UW Reality Labs Icon">

paper in progress!

## Abstract

We attempt to provide a mechanical varifocal solution to the vergence-accommodation conflict present in today's consumer virtual and mixed reality headsets. The varifocal display system consists of a single biconvex lens set at a fixed position, with the display modules for the eyes being set between the focal length of the lens and the lens itself. We achieve dynamic focal distances by moving the displays closer and further from the lens via stepper motors. To quickly and accurately approximate where in the virtual scene the user is looking, we implement real-time gaze-tracking with XIAO ESP32S3 Sense cameras and software courtesy of the open-source project EyeTrackVR. We create a ray cast from the user's eyes in the Unity game engine to find the object in focus and calculate its distance from the user. This proves as the basis for the varifocal display system.

Using the prototype and an example Unity scene, we attempt to empirically prove the benefits of varifocal technology with an internal study. Lastly, we discuss the limitations of only moving the display modules versus other methods of achieving a varifocal display system.