[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=14)

# ScreenshotsNanny

##Introduction
Until the time of writing, the Android toolchain doesn't have anything to help take screenshots automatically for publishing on Google Play Store.

The other fact is that most of the modern apps consume internet resources, or have UGC (user-generated content).  And for the screenshots showing on Google Play, no one would like to see any arbitrary content which may be ugly or even inappropriate.

Be professional!  Be beautiful!  You can achieve it easily by using ScreenshotsNanny.

##Comparison
Below are two different screenshots for the same activity.  The left one is using real arbitrary content, while the right one is using prepared mock response.

![Comparison](https://cloud.githubusercontent.com/assets/352956/11276098/e8e25434-8ee0-11e5-9685-df75085859e6.png)

##Setup & Sample code
Please check out the demo module along with this project.
```java
```

##Screenshots
* The Android Status Bar won't be captured as part of the screenshot, so you don't have to worry about the messy icons there.
* MapView (no matter if it fulfills the window or not) will also be taken into the screenshot.
* For any activity consumes network resources, you can replace the content by canned mock response.  (This library is using [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver) from [Square, Inc.](https://github.com/square))
* Some activities may read values from persistent data (e.g. SharedPreferences), you can also prepare the values before activity starts.

<a href="https://cloud.githubusercontent.com/assets/352956/11317838/3032f606-903d-11e5-914d-cd37a07ca147.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11317838/3032f606-903d-11e5-914d-cd37a07ca147.png" height="300"></a>
<a href="https://cloud.githubusercontent.com/assets/352956/11317839/35be90ee-903d-11e5-83bf-3c6e33e08f3c.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11317839/35be90ee-903d-11e5-83bf-3c6e33e08f3c.png" height="300"></a>
<a href="https://cloud.githubusercontent.com/assets/352956/11317840/3fbbee34-903d-11e5-8275-1863646bfdc3.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11317840/3fbbee34-903d-11e5-8275-1863646bfdc3.png" height="300"></a>
<a href="https://cloud.githubusercontent.com/assets/352956/11317843/48208760-903d-11e5-991d-371d65f0eee4.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11317843/48208760-903d-11e5-991d-371d65f0eee4.png" height="300"></a>
<a href="https://cloud.githubusercontent.com/assets/352956/11317844/4eb2770a-903d-11e5-98f4-5ccc7ea4ee7c.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11317844/4eb2770a-903d-11e5-98f4-5ccc7ea4ee7c.png" height="300"></a>

(sorry, these demo activities layouts were made with poor design, look ugly)

##Logs

![Logs](https://cloud.githubusercontent.com/assets/352956/11317845/54ddb72a-903d-11e5-814f-0ebeb3872e07.png)

##License
Copyright (c) 2015 Jing Li. See the LICENSE file for license rights and limitations (MIT).

##Last but not least
This is made in Berlin with love and passion ʕ´•ᴥ•`ʔ

<a href="../../" target="_blank"><img src="https://cloud.githubusercontent.com/assets/352956/11226672/b2a693fe-8d81-11e5-8d87-7f507d63e029.png" height="200"></a>
