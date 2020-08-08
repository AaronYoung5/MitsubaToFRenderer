# MitsubaToFRenderer
Mitsuba renderer with support for time-of-flight rendering. See INSTALL.txt for cloning and installation of the MitsubaToFRenderer. See USAGE.txt for running the MitsubaToFRenderer with various settings. See INSTALLEXR2AVI.txt to install exr2avi scripts and view/save the exr output of the MitsubaToFRenderer as an image or video. 

You can run this renderer on AWS using two pre-configured AMIs with ID ami-28308957 (us-east-1, N. Virginia) and ami-00329ef32ac692d6c (us-east-2, Ohio). Both AMIs are compatible with [CfnCluster](https://cfncluster.readthedocs.io/en/latest/) for easy distributed rendering.

# project page:
http://imaging.cs.cmu.edu/ellipsoidal_connections/

# credits: 
The project is derived from https://www.mitsuba-renderer.org/ and https://github.com/cmu-ci-lab/mitsuba_clt.git (for coded projector and coded camera extension). 
On top of these, the ToF renderer and ellipsoidal connections for time-gated rendering are added.


The scene file can be created by using the mitsuba documentation (https://www.mitsuba-renderer.org/releases/current/documentation.pdf)
Please refer to https://github.com/cmu-ci-lab/mitsuba_clt/blob/master/README.md for creating scenes with coded projector and coded camera. 

If you have used the renderer, please cite "Adithya Pediredla, Ashok Veeraraghavan, and Ioannis Gkioulekas. "Ellipsoidal Path Connections for Time-gated Rendering", SIGGRAPH 2019 
