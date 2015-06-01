0.8.0
- Changed distance treshold methods to work with ints instead of floats
	Distance mesure in cm for each int.
	  setLowThresholdPC(int);
  	  setHighThresholdPC(int);
- Elimanated the toggle  enableSkeleton(bool)
	three new functions to activate Skeleton mapping
	  	enableSkeletonColorMap(bool);
	    enableSkeletonDepthMap(bool);
	    enableSkeleton3dMap(bool);
 - Naming of the KQuaternion  class
 - Face tracking for the infrared Img and color Img.

0.7.2