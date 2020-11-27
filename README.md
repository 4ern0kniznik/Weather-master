# Weather

<p align="center">
  <img src="screenshot/logo.png" >
</p>


#### Used libraries:
* com.android.support:appcompat-v7:25.1.0
* com.android.support:support-v4:25.1.0
* com.android.support:recyclerview-v7:25.1.0
* com.android.support:design:25.1.0
* com.android.support:cardview-v7:25.1.1
* org.greenrobot:greendao:3.2.0
* com.squareup.retrofit2:retrofit:2.1.0
* com.squareup.retrofit2:converter-gson:2.1.0
* com.squareup.okhttp3:logging-interceptor:3.3.1
* com.google.android.gms:play-services-location:10.2.0
* com.firebase:firebase-jobdispatcher:0.5.2

#### Prerequisites

Create an api.gradle file in Weather directory after generating API Key from Apixu and UserName from GeoNames. The contents would somewhat look like this :

    ext {
    BASE_WEATHER_URL = "http://api.apixu.com/v1/"; 
    BASE_GEONAME_URL= "http://api.geonames.org/"; 
    GEONAME_API_KEY= "YOUR_USER_NAME"; 
    WEATHER_API_KEY = "YOUR_API_KEY"; }


