# Hand-Gestures

Adjusting the brightness of screen varies result. 
try to position hand completely in the box and avoid arm or wrist coming in the box(as it will change the arearatio). 
done using range values so may work for different color ranges for different people.

------------------------------------------------------------------------------------------------------------------------------------
Changed line 42 to

  contours,hierarchy= cv2.findContours(mask,cv2.RETR_TREE,cv2.CHAIN_APPROX_SIMPLE)	
