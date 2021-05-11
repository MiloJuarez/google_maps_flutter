# Google Maps in Flutter

App that uses Google Maps and connect to Google's web services to get all their offices locations
in order to display them in the maps

## Getting Started

Before you run the app, you've to setup two pre-requisites to use google maps.
The first thing you have to do is create an API key in your google developer account, this link (https://developers.google.com/maps/documentation/android-sdk/get-api-key) will show you how to do it (For this app, just create the API key). If you already have projects, just select one, then follow the instructions, else continue as follows. Once the API key is created, you have to put it in the android/app/src/main/AndroidManifest.xml file:

![image](https://user-images.githubusercontent.com/48868937/117866711-0de8df00-b25d-11eb-8b16-68199b1f74b7.png)


After that, is neccesary to put the API key in the ios/Runner/AppDelegate.swift file as well: 

![image](https://user-images.githubusercontent.com/48868937/117867010-6ae49500-b25d-11eb-912d-756c8fa8dcad.png)

Here, we have imported GoogleMaps and added the line: GMSServices.provideAPIKey("YOUR_API_KEY")
# Note: Is recommended create an API key for both Android and iOS

Once everything is done, you could run the app and see a result like this:

![Screenshot_1620758241](https://user-images.githubusercontent.com/48868937/117867473-0b3ab980-b25e-11eb-911b-5b60ba32a318.png)
