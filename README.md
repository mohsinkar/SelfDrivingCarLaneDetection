# SelfDrivingCarLaneDetection



<b>The following processes are performed in the this function</b>

1. Image is conveted to HSV <br/>
2. Color range is defined for white color lanes <br/>
3. Color range is defined for yellow color lanes <br/>
4. Yellow color is extracted from the image using inRange  <br/>
5. White color is extracted from the image using inRange <br/>
6. The two images extracted yellow and extracted white is combined. <br/>
7. Applied canny on the combined image <br/>
8. Reduced the selection to the desired region. <br/>
9. Hough trasform on the region. <br/>
