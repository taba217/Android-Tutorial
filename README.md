# Android-Tutorial

1) BasicActivitySwitch - Creating two simple activities, reading the data from activity one and passing the same data as an intent to the next activity.
2) REST API using volley library
Note : For excluding the duplicate entry use this.
implementation 'com.android.volley:volley:1.1.1'
    android{
        configurations {
            all*.exclude group: 'com.android.volley'
        }}
