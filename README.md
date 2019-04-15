<b>Telegram March contest 2019. (2 weeks)</b> 
(link to April contest - https://github.com/opiumfive/android_chart_stage2)

Goal is to show simple charts.

The criteria to define the winner are speed, efficiency and the size of the app.

<b>Result apk (as it was uploaded - from initial commit):</b> 

https://github.com/opiumfive/android_chart_stage1/blob/master/TeleChart.apk

<b>Small result video:</b> 

https://github.com/opiumfive/android_chart_stage1/blob/master/telechart_demo.mp4

<b>Adaptive Kalman filter performance demos:</b> 

https://github.com/opiumfive/android_chart_stage1/blob/master/kalman1.mp4
https://github.com/opiumfive/android_chart_stage1/blob/master/kalman2.mp4

<b>Some notes:</b> 
- done by simple 2d canvas rendering without any TextureView, SurfaceView or OpenGLES;
- fling support
- smooth Min/max adjusting made by Kalman filter adjusted with scroll velocity;
- line check/uncheck animation by valueanimator;
- optimized for small screens, for landscape mode with saving state;
- 60 fps on last 4-lines chart on most devices;
- circular reveal theme changing;
- apk size 168kb (because without appcompat and using java not kotlin).

<b>Known issues:</b>
- X, Y labels animations not pretty work

<b>Telegram review:</b>
Thank you for taking part in the Telegram March Competition for Android developers. Below we would like to share our feedback on your app with you:

Unfortunately, your app doesn't fully comply with the design guidelines provided for the contest. Values on the graphs jitter when the page is scrolled.

Please note that the task was to display the graphs on the same page.

We hope that you enjoyed the first stage of the contest. You are welcome to take part in the next stage (April, 6-15).
