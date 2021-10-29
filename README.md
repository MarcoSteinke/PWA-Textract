# PWA-Textract
Simple PWA which shall be deployed on android devices. Its main functionality will be after taking a screenshot this application will be listed in the "send screenshot to" menu and can extract URL's from a screenshot without saving this screenshot on your device!


## Structure:

* Website
* Android Application
* API
* Webapplication


## Features:

* Android Application:
  * send Screenshot to App
  * display all found URL's from the screenshot in a list
  * make the list items interactable to copy or visit the URL
* Website:
  * Inform the user
  * Product Presentation
  * Legal information
* API:
  * Receive requests including screenshots
  * Throw the screenshots in the integrated AI model
  * return the result to either the Webapplication or the Android Application
  * store information about each request for data analysis and marketing purposes
* Webapplication:
  * display all found URL's from the screenshot in a list
  * make the list items interactable to copy or visit the URL
  * send requests to the api
