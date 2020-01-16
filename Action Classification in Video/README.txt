This was a 2-person assignment for my Computer Vision course, written in C++ using a computer vision library called OpenCV. We were given information about a camera setup in one of the university's labs, where multiple cameras were placed on various points in a room that recorded footage of three people walking around the room. The goal was to track the three people's movement in a 3D space.

This was done by separating the foreground (the people) from the background (the university lab) in each camera feed, reconstructing a 3D space using the camera feeds, using the intersections of the foreground pixels on each feed to create the 3D representations of each person, and then constructing and using histograms of the colours that they were wearing to differentiate the people. This allowed us to track their path around the lab.

The Video folder has two videos showing the work done, with the INFOMCV_P2 video showing the foreground/background separation and the INFOMCV_P3 video showing the voxel-based tracking.

Repo: https://github.com/StephanWells/INFOMCV_P4