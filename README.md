AerisAndroidSDK
================

The Aeris Android SDK allows a developer to quickly and easily add weather content and functionality to their android applications. It utilizes the Aeris API backend for data loading and is built on top of an object mapping system that efficiently loads requested weather content into third-party Android applications, greatly reducing the amount of code and development needed on the developer end.

## Getting Started 

View the latest installation and implementation details in the [Aeris Android SDK docs](http://www.aerisweather.com/support/docs/toolkits/aeris-android-sdk/getting-started/).

### Aeris API Configuration for the AerisDemo App
Before you can begin using the Aeris Android SDK in your project, you will need to download the latest version of the SDK and ensure that you have the required Aeris API keys for your application.

Step 1: Get the files.  Download the latest version of the Aeris Android SDK. 

Step 2: Get access to the Aeris API. 

To use the Aeris API, you will need to have valid access keys. Access keys are obtained by registering your application/namespace. To register your application, log in to Aeris Weather with your account and look for "APPS". 
Don't have an Aeris account? You can get one for free [here](https://www.aerisweather.com/signup/pricing/).

Step 3: Determine which components of the Aeris Android SDK you need for your project:

### Aeris Core library
This is the base library for accessing the AerisWeather API. If you are planning to use the Aeris API for data without a map component, this is all you need.

### Aeris Map library
This library provides access to AerisWeather mapping features such as radar, satellite, warnings, etc. 
The map library includes a dependency to the Aeris Core library, so you won't need to download the Core library separately. If you are planning to use Aeris to create weather maps for your Android project, this is the library for you.

Step 4: Include the Aeris Android SDK files in your project's gradle.build file(s).

## Aeris Demo App
The SDK includes a demo app to help get you started. To allow the demo project to access data using the Aeris API, you will need to configure the Aeris Demo project to use your unique credentials. Just sign up for a free developer account and register yourself and your application with AerisWeather, to get your unique client Id and secret.

For more details please visit the following links:

##Reference Links
[Aeris API Docs](http://www.aerisweather.com/support/docs/api/).<br/>
[Aeris API Signup](http://www.aerisweather.com/signup/).<br/>
[Aeris Mapping Platform (AMP) ](https://www.aerisweather.com/develop/#maps).<br/>
[Aeris Android SDK](http://www.aerisweather.com/support/docs/toolkits/aeris-android-sdk/).<br/>
[Aeris Android Core Library Javadocs](http://www.aerisweather.com/docs/android/Aeris/index.html).<br/>
[Aeris Android Maps](http://www.aerisweather.com/support/docs/toolkits/aeris-android-sdk/getting-started/weather-maps/).<br/>
[Aeris Android Maps Library Javadocs](http://www.aerisweather.com/docs/android/AerisMap/index.html).<br/>
