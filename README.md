# How_android_display_system_working

In Android Platform Image Stream can be Produced by OpenGLES, media Player, Camera view and NDK. Hence these are the Producer of Image. 

Everything is renedr onto a SURFACE. The surface represents the producer side of a buffer queue that is often consumed by SurfaceFlinger.
Every window that is created on the Android platform is backed by a surface.
All of the visible surfaces rendered are composited onto the display by SurfaceFlinger.

The Most 




## Ref
  * [link] (https://source.android.com/docs/core/graphics)
