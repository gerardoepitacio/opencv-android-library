# opencv-android-library
OpenCV 3.4.3 Android Library on Android Studio ArticFox Canary 15

Converted to Android studio project of Android version of OpenCV

Compiling the .aar library.
1. Download the repo
2. in the root folder run the following command ./gradlew opencv343:bundleReleaseAar
3. locate your .aar file in /opencv343/build/outputs/aar/opencv343-release.aar
4. Copy the aar file to libs folder of your application -> app/libs
5. Include .arr library in the build.gradle of your application

// build.gradle (application)
dependencies {

    // other dependencies...
    
    // opencv dependency
    implementation name: "opencv343-release", ext: 'aar'
}

6. Sync your project and walaaa! :D.

remember you have the rest of the files into jniLibs asss indidcate
https://medium.com/android-news/a-beginners-guide-to-setting-up-opencv-android-library-on-android-studio-19794e220f3c

