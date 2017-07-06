# ZoomImageView-lib

<img src="Screenshot/20170706_184348.gif" width="300">

## How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.andy6804tw:ZoomImageView-lib:0.0.1'
	}
Share this release:

[![](https://jitpack.io/v/andy6804tw/ZoomImageView-lib.svg)](https://jitpack.io/#andy6804tw/ZoomImageView-lib)


## XML
```XML
<com.andy6804tw.zoomimageviewlibrary.ZoomImageView
        android:id="@+id/zoomImageView"
        android:layout_width="wrap_content"
        android:layout_height="200dp"
        android:layout_marginTop="30dp"
        android:src="@mipmap/image" />
```

It extends ImageViwe so you can using this library as same as origin function.
