# fileUploadingGoogleDrive
Simple script to upload files on Google Drive

Step 1: Turn on the Drive API

a. Use this wizard to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials. b. On the Add credentials to your project page, click the Cancel button. c. At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button. d. Select the Credentials tab, click the Create credentials button and select OAuth client ID. e. Select the application type Other, enter the name "Drive API Quickstart", and click the Create button. f. Click OK to dismiss the resulting dialog. g. Click the file_download (Download JSON) button to the right of the client ID. h. Move this file to your working directory and rename it client_secret.json.

Step 2: Install the Google Client Library

Run the following command to install the library using pip:

pip install --upgrade google-api-python-client See the library's installation page for the alternative installation options.

Setp 3: python fileUploadingGoogleDrive.py

The script will attempt to open a new window or tab in your default browser. If this fails, copy the URL from the console and manually open it in your browser.

If you are not already logged into your Google account, you will be prompted to log in. If you are logged into multiple Google accounts, you will be asked to select one account to use for the authorization. Click the Accept button. The script will proceed automatically, and you may close the window/tab.
