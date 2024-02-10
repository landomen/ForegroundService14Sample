# Android 14 - Foreground Service Sample

This sample app demonstrates how to use the foreground service on Android 14.
It is meant as a companion to the **[Guide to Foreground Services on Android 14](https://medium.com/@domen.lanisnik/guide-to-foreground-services-on-android-9d0127dc8f9a)** blog post.

Included are the following functionalities:
 - Starting a foreground service with a declared foreground service type of location
 - Requesting location permissions before service is started
 - Binding to the foreground service from Activity to display the service status and receive location updates
 - Stopping the service from the activity
 - Requesting notification permission to show foreground service notification

**Previews**

<p float="left">
  <img src="/previews/preview0.png" width="19%" />
  <img src="/previews/preview1.png" width="19%" /> 
  <img src="/previews/preview2.png" width="19%" />
  <img src="/previews/preview3.png" width="19%" />
  <img src="/previews/preview4.png" width="19%" />
</p>

**References**
- https://medium.com/@domen.lanisnik/guide-to-foreground-services-on-android-9d0127dc8f9a
- https://developer.android.com/develop/background-work/services/foreground-services
