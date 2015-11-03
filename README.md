# WclDemoSample
* This is a sample app that shows how one can set up an application to use the
  WearCompanionLibrary. It has both a phone and a wear component.
  You can drive this sample from either your phone or your wear device. On your mobile, select
  a page from the drawer and there, you can open the corresponding page on your
  wear device by pressing on the FAB button at the lower right corner of the page. On your
  wear device, you can select an item form the list when you run the app. Features
  shown includes exchanging data, launching remote app, making HTTP calls from the wear
  device and showing variations of WearableListView activities. Note that on your mobile phone you
  have to be on page corresponding to the wear page to be able to see the feature.

## Dependencies
* [WearCompanionLibrary (WCL)](https://github.com/googlesamples/android-WearCompanionLibrary)
* The phone module also depends on the [design support library](http://android-developers.blogspot.com/2015/05/android-design-support-library.html).
* Note: if you follow the instructions below, the WCL library will bring in other dependencies that
  are needed. If you choose to use WCL in a different way (for example using an archive version of
  that library), then you may need to include the dependencies that are listed for WCL as well.

## Setup
* Checkout this project as WclDemoSample:
  $ git clone https://github.com/googlesamples/android-WclDemoSample WclDemoSample
* Checkout WCL as a sibling to this project:
  $ git clone https://github.com/googlesamples/android-WearCompanionLibrary WearCompanionLibrary
* To make sure all is working, compile WCL:
  $ cd WearCompanionLibrary && ./gradlew build
  This should successfully compile WCL.
* Compile this project:
  $ cd ../WclDemoSample && ./gradlew build
* To open the project in Android Studio, you may need to first open the WCL project in Android Studio
  to build the required "*.iml" file for Android Studio. To do this, start Android Studio and select "Open An Existing
  Android Studio Project" and navigate to WCL directory and select the build.gradle in the root of
  that project. This should create the needed files.
* Close Android Studio and open that again and follow the same steps but this time navigate to
  WclDemoSample project and select build.gradle there.


## References and How to report bugs
* WCL has a documentation (in PDF format) in its project. This code has comments that along with the
  WCL's documentation should be adequate to guide you through the sample.
* If you find any issues with this sample, please open a bug here on GitHub; if you find any issue
  with WCL or have a feature request, please open a ticket on that repository.

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING

## License
See LICENSE

## Change List
1.0
 * Initial release
