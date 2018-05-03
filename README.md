# Access API Sample App

**Required:**
* Latest version of Android Studio 
* Device with Passcode and/or Fingerprint locks enabled

## Get Started
1. Open the project 'MASAccessAPISample' in Android Studio
2. Go to your CA Mobile API Gateway policy manager (or Mobile Developer Console if you have one), create an app, and export the msso_config (https://you_server_name:8443/oauth/manager) For more info, see [Android Guide](https://www.ca.com/us/developers/mas/docs.html?id=1).
3. Copy all contents of the exported msso_config into: src/main/assets/msso_config.json.
4. Import /utils/tradePolicy.xml into your policy manager as an endpoint with the resolution path '/trade'.
5. Build and Deploy the app to a device.
