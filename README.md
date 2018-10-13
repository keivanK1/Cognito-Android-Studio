# Addind AWS Cognito Sign in and Sign up to Android App

Simple user authentication in Android App using AWS Cognito. 

## Requirements

* Android Studio
* AWS Account
* AWS Cognito Userpool

## Getting Started

* Clone the repository:

      git clone https://github.com/keivanK1/Cognito-Android-Studio.git
* Change the following variable in `Cognito.java` to yours Cognito userpool parameters:
      
      private String poolID = "Place_Your_UserPoolID";
      private String clientID = "Place_Your_ClientID";
      private String clientSecret = "Place_Your_ClientSecret";
      private Regions awsRegion = Regions.DEFAULT_REGION;         // Place your Region
* Open a Beer and run the App
