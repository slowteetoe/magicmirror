# magicmirror
extremely basic android app that just displays a webview as the default home screen

### Todo
* The screen is always on (Enable 'developer settings' by going to Settings -&gt; About and tapping on build number until it shows up, 7 taps I think... Once you have developer settings enabled, make 'Stay Awake' checked)  I don't know if we need to worry about screen burn-in like on older monitors, but it would probably be good to turn it off while no one is around.  I should enable motion detection, maybe just something rudimentary like using the camera API every few seconds, computing a smaller grid from the photo and seeing if it changes should work for this app since the mirror will just be hanging on a wall
* Enable facial recognition - should be able to get OpenCV or JavaCV running on the Nexus 7, it would be cool to have different webviews based on who is in front of the mirror at the moment
