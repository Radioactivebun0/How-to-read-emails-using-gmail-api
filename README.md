# How-to-read-emails-using-gmail-api
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

14. Configure the credentials by clicking on Credentials within the tab APIs and Services

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step8.png?raw=true" width="400" />

15. Click Create Credentials and then OAuth client ID

16. Set the application type to Desktop Application

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step9.png?raw=true" width="400" />

17. Under name enter any name

18. Press CREATE at the bottom of the page

19. Press the download button to dowload the Credentials to your computer

<img src="https://github.com/Radioactivebun0/How-to-read-emails-using-gmail-api/blob/main/pics/step10.png?raw=true" width="400" />

20. Rename the download file to `credentials.json` and put it in the same dictionary as main.py, which can be dowloaded from this repository

21. Run main.py, if it is your first time, you will be prompted to sign into your google account. You can only sign in with gmail accounts that where defined as test users in step 10

For more information on how main.py works, look at the Geeks for Geeks link for an explination. 

## If you need any help, create an issue and ill do my best to help you

Thanks to Geeks for Geeks for the information and code that this uses 

I found some of the steps to be outdated so thats why I created these steps, but most of them should be the same if you need another reference.

https://www.geeksforgeeks.org/how-to-read-emails-from-gmail-using-gmail-api-in-python/
