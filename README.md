# AR library for Processing-Android Utility Files and Classes

![Android](https://img.shields.io/badge/platform-Android-green.svg?longCache=true&style=for-the-badge)   ![ARCore](https://img.shields.io/badge/ARCore-v1.2.0-blue.svg?longCache=true&style=for-the-badge)   ![In Progress](https://img.shields.io/badge/in--progress-true-green.svg?longCache=true&style=for-the-badge) <br />
Contains changes that has to be done in Build files outside the AR Library - Android Mode plus the templates for Manifest, Theme, Gradle files and so on for AR in Processing-Android.

## Contains:
* Changes in the following files to make AR functional in Android mode.<br />
Under `android-mode` Module, following shows the directory traversal: <br />
    * `src -> processing.mode.android -> AndroidBuild.java` <br />
    * `src -> processing.mode.android -> AndroidEditor.java` <br />
    * `src -> processing.mode.android -> Commander.java` <br />
    * `src -> processing.mode.android -> Manifest.java` <br />
* Created standard templates for sketches that relay on <b>AR</b> under the `templates` Directory.<br />
* Changes in the Module level `build.gradle` and `build.xml` files to get it up and running in the android-mode

## TODO:
* Refining permission in `Manifest.java` for AR. <br />
* Defining <b>Themes</b> in `Manifest.xml.tmpl`. <br />
* Incomplete `ARActivity.java.tmpl`.<br />
<b>NOTE:</b> Can be designed only after `ar.jar` is ready and functional. <br />

## Working:
<p align="center">
  <img src="imgs/sk_2.gif">
</p>