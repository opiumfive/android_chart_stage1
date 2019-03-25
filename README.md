<b>Telegram March contest 2019.</b> 

Goal is to show simple charts.

The criteria to define the winner are speed, efficiency and the size of the app.

<b>Result apk:</b> 

https://github.com/opiumfive/android_chart_canva/blob/master/TeleChart.apk

<b>Small result video:</b> 

https://github.com/opiumfive/android_chart_canva/blob/master/telechart_demo.mp4

<b>Some notes:</b> 
- done by simple 2d canvas rendering without any TextureView, SurfaceView or OpenGLES;
- fling support
- smooth Min/max adjusting made by Kalman filter adjusted with scroll velocity;
- line check/uncheck animation by valueanimator;
- optimized for small screens, for landscape mode with saving state;
- 60 fps on last 4-lines chart on most devices;
- circular reveal theme changing;
- apk size 168kb (because without appcompat and using java not kotlin).
