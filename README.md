![](instructions.gif)

# FocalPointViewer
 Scripts to make setting the focal point easy
 How to use:<br>
Select your camera.<br>
Run createFocalPlane.dsa<br>
use the Z translate to adjust the plane's distance to the camera.<br>
Run planeToCamera.dsa<br>
You can now delete the plane.<br>
<br>
<br>
Notes:<br>
1. You can change the plane's scale / surface to make it easier to see<br>
2. The plane is a child of the camera so feel free to rotate or move the camera<br>
3. Only move the Plane using the Z translate //OR// Set Use Local Coordinates for the Translate tool to be able to drag the plane around by the Z gizmo.<br>
<br>
<br>
Mirrors!<br>
Run CreateFocalAndMirrorPlane.dsa<br>
Select the mirror plane - use it's Z translate to adjust the mirror plane's distance to the camera. use it to move the plane so its centre intersects mirror<br>
Select the subect plane - use it's Z translate to adjust the subject plane's distance from the mirror to the subject. use it to move the plane so its centre intersects subject<br>
Select the Camera and run setMirrorFocus.dsa<br>
You can now delete the planes.<br>