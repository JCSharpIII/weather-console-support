# Privacy Policy

**Effective Date:** November 6, 2026  
**Application Name:** Weather Console  
**Developer:** James C. Sharp  

### Overview
**Weather Console** ("the App") is designed to provide real-time weather telemetry from Davis Instruments WeatherLink stations and compatible local air quality monitors. Your privacy is important to us. This Privacy Policy outlines how information is handled when you use the App.

### Information Collection & Usage
* **No Personal Data Collection:** The App does not collect, store, harvest, or transmit any personal information (such as your name, email address, location, or device identifiers) to the developer.
* **API Credentials:** To connect to your weather station, the App requires your WeatherLink v2 **API Key** and **API Secret**. These credentials are entered directly by you and are stored **locally and securely** on your device using Apple's encrypted system storage (`UserDefaults` / `AppStorage`). They are never shared with third parties or transmitted to any external servers other than official Davis Instruments WeatherLink API endpoints (`api.weatherlink.com`) required to fetch your weather data.
* **Demo Station Mode:** When operating in Demo Station Mode, the App uses built-in simulated data or Davis Instruments' public developer demo station. No user data is gathered or logged during this process.

### Third-Party Services
The App communicates directly with the **WeatherLink v2 Cloud API**, managed by **Davis Instruments**. Any data retrieved by the App is governed by Davis Instruments' terms and data services. For more information on how Davis handles cloud data, please refer to their official privacy guidelines.

### Data Security
All communications between the App and the WeatherLink API are encrypted using HTTPS. HMAC-SHA256 request signing is utilized to ensure your API credentials remain secure during authentication.

### Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated effective date.

### Contact Us
If you have any questions or suggestions about this Privacy Policy, please reach out via your developer support contact or repository.
