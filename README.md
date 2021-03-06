# imgur-android

<p>
  A basic upload tutorial using imgur API v3 on Android. Select an image via an intent, then upload that image with or without a title/description.<br><br>
  I'm assuming you follow the official API instructions from imgur: <a href="https://api.imgur.com/">here</a><br><br>
  All API calls are done using <a href="http://square.github.io/retrofit/">Retrofit</a>
</p>

This is a fork that adds clipboard support, i.e. once the image is uploaded, the link is stored in the clipboard.

<h2>Configuration</h2
<p>Just about everything you need is setup for you.<br>
<ul>
  <li>Import the project into Android Studio</li>
  <li>In <b>Constants.java</b> add your imgur Client API key in the static field: <i>MY_IMGUR_CLIENT_ID</i></li>
</ul>
</p>

<h2>Results</h2>
<p>
  <img src="http://i.imgur.com/sSM5Hja.jpg" height=500 width=300></img>
  <img src="http://i.imgur.com/CHrRpu6.png" height=500 width=300></img>
  <img src="http://i.imgur.com/0LtqQXs.png" height=500 width=300></img>
</p>


