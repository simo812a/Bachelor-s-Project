
# Virtuel Webcam Setup Guide

> **Virtualization of sound**
 1. Download and install OBS (Open Broadcaster Software) from: https://obsproject.com/da
 Installation instructions for Windows, Linux and MacOS can be found at: https://obsproject.com/wiki/install-instructions
 
 2. Download and install Spectralizer for OBS. Download link and installation guide can be found at: https://obsproject.com/forum/resources/spectralizer.861/
 3. Open OBS then add a new scene by pressing the **+** icon in the lower left corner of the **Scenes**-box. Title this however you would like e.g. "Audio Activity - Webcam"
 4. Next add a new souce by pressing the **+** icon in the lower left corner of the **Sources**-box, choose **Picture** from the list. Press **OK**, then browse and choose a profile picture - This will be the picture that others will see behind the audio activity.
 5.  Add another souce by pressing the same **+**  again, this time choose **Spectralizer**. 
	 - For **mode** choose **wire** in the drop down menu.
	 - For **Audio souce** choose the perfered microphone.
	 - _Optional:_ change the color of the wire by clicking **select color** and choosing the perfered color.
	 - For **Wire mode** choose **Custom thickness**. The deafult **Wire thickness** is 5 pixels, change this to 10 instead.
 6. Resize and reposition the audio wire so that it fits the picture chosen. Make sure that it is on top of the picture, by dragging it to the top of the list of sources. 
 7. Press **Start Virtual Camera** to start the virtual camera, then select "OBS Camera" as your **webcam** in your perfered application.
 > **Silhouette**
 
 1. Download and install OBS (Open Broadcaster Software) from: https://obsproject.com/da
 Installation instructions for Windows, Linux and MacOS can be found at: https://obsproject.com/wiki/install-instructions
 
2. Download and install XSplit VCam (Windows only) from: https://www.xsplit.com/vcam
 Installation instructions can be found at: https://www.xsplit.com/support/vcam/getting-started
 3. Open XSplit VCam and follow the setup instructions. Login is optional and can be skipped. Make sure to select the right webcam in the dropdown menu at the top once setup is done.
 4. On the right select **Remove** below **Background**. White and grey squares should now replace your background.
 5. Next open OBS then add a new scene by pressing the **+** icon in the lower left corner of the **Scenes**-box. Title this "Webcam Silhouette Effect" or similar.
 6. Select this scene and then add a new souce by pressing the **+** icon in the lower left corner of the **Sources**-box, choose **Video Capture Device** from the list. Press **OK**.
	 - For **Device** choose the perfered webcam in the drop down menu.
	 -  _Optional:_ change the resolution of the output by selecting **Custom** in the **Resolution/FPS Type** tab, and then selecting the perfered resolution e.g. 1920x1080 or 1280x720.
	 - When done press **OK**.
3.  Right click the scene that was just made (the one titled "Webcam Silhouette Effect"), and select filters.
	- Add a new filter by pressing the **+** icon in the lower left corner of the **Effectfilters**-box.
	- Select **Color Correction**
	- Drag the **Brightness**-slider all the way to the left, so that its value is "-1,00"
4. Add another scene, this time title it however you would like e.g. "Live Webcam Silhouette".
	- Select this scene and add a new source, choose **Scene**. Under **Add Existing** select the previous scene that was just created (the one titled "Webcam Silhouette Effect")
	- Add another source, choose **Color source**. Click **Select color** and pick a color for the background e.g. white.
	- When done press **OK**
5. Make sure that the video source  is on top of the color source, by dragging it to the top of the list of sources.
6.  Press **Start Virtual Camera** to start the virtual camera, then select "OBS Camera" as your **webcam** in your perfered application.
 > **Virtuel background / blur**
 1. Download and install XSplit VCam (Windows only) from: https://www.xsplit.com/vcam
 Installation instructions can be found at: https://www.xsplit.com/support/vcam/getting-started
 2. Open XSplit VCam and follow the setup instructions. Login is optional and can be skipped. Make sure to select the right webcam in the dropdown menu at the top once setup is done.
 3. To blur out the background use the slider below the preview window.
 4. To change the background choose one on to the right of the preview window. Press **Add background** to add a cumtom background to the webcam.
 5. Select "XSplit Vcam" as your **webcam** in your perfered application to use either a blurred out or cumtom background.
