# How-to-read-emails-using-gmail-api
# Still creating the steps
Steps to read emails using gmails api in python:

1. Install the required google libraries by running: `pip3 install –upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`

2. Run this to install Beautiful Soup: `pip3 install beautifulsoup4`

Now we have to set up Google Cloud consle to allow us to interact with the Gmail API:

1. Sign in to Google Cloud console and create a New Project or continue with an existing project. You can use this link: https://console.cloud.google.com/

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step1.png?raw=true" width="400" />

2. Go to APIs and Services

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step2.png?raw=true" width="400" />

3. Go to the search bar and type, "gmail" and press enter. Gmail API should be the first result, click on it.

4. Press enable

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step3.png?raw=true" width="400" />

5. Configure the Consent screen by clicking on OAuth Consent Screen within the tab APIs and Services

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step4.png?raw=true" width="400" />

6. Click on External and Create 

7. Enter an App Name and an User Support Email, the name can be whatever you want it to be and the User Support Email should me the gmail of the account you are using.

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step5.png?raw=true" width="400" />

8. Scroll to the bottom of the page and under Developer contact information enter a valid email

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step6.png?raw=true" width="400" />

9. On step 2, Scopes, scroll to the bottom of the page and press save and continue

10. Under Test users press ADD USERS 

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step7.png?raw=true" width="400" />

11. Add one or multiple valid gmails and press ADD, these gmail will be the only ones that can use this api

12. Press Save and Continue 

13. This brings you to the Summary tab, scroll to the bottom and press BACK TO DASKBOARD



Thanks to Geeks for Geeks for the information and code that this uses 
https://www.geeksforgeeks.org/how-to-read-emails-from-gmail-using-gmail-api-in-python/
