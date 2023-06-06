# Azure Application Setup

This guide provides step-by-step instructions to register your app in the Azure portal.

## Prerequisites
- Microsoft account credentials

## Steps

1. Go to the Azure portal: [Azure Portal](https://portal.azure.com/) and sign in with your Azure account credentials.
![Step 1](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s1.png?raw=true)
2. In the search bar, type "App registrations" and select "App registrations" from the suggestions.

3. Click on the "New registration" button to create a new app registration.

4. Provide a name for your app registration, such as "TestingApp". Choose the appropriate option for the "Supported account types" based on your requirements. In the "Redirect URI" section, select "Web" as the type and enter the redirect URL for your application. This URL is where users will be redirected after authenticating with GitHub. For local development, you can use "http://localhost:3000" or any other URL that matches your application's requirements. Once you have provided all the necessary information, click on the "Register" button.

5. After the app registration is completed, you will be redirected to the overview page of your app. Take note of the "Application (client) ID" as you will need it later to configure your application.

6. Search for "API Permissions".

7. Click on "Add Permission" Button.

8. Select "Microsoft Graph"

9. Choose "Delegated permissions" and navigate to "Files". 

10. check all the permissions that are required for your case as for accessing purposes Files.ReadWrite.All and Files.ReadWrite are checked.

11. Search for "Authentication".

12. Enable the Access token in the Authentication tab to ignite your application with the power of authentication. Click "Save" to apply the changes.
