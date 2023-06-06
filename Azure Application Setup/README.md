# Azure Application Setup

This guide provides step-by-step instructions to register your app in the Azure portal.

## Prerequisites
- Microsoft account credentials

## Steps

1. Go to the Azure portal: [Azure Portal](https://portal.azure.com/) and sign in with your Azure account credentials.

![Step 1](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s1.png?raw=true)

2. In the search bar, type "App registrations" and select "App registrations" from the suggestions.

![Step 2](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s2.png?raw=true)

3. Click on the "New registration" button to create a new app registration.

![Step 3](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s3.png?raw=true)

4. Provide a name for your app registration, such as "TestingApp". Choose the appropriate option for the "Supported account types" based on your requirements. In the "Redirect URI" section, select "Web" as the type and enter the redirect URL for your application. This URL is where users will be redirected after authenticating with GitHub. For local development, you can use "http://localhost:3000" or any other URL that matches your application's requirements. Once you have provided all the necessary information, click on the "Register" button.

![Step 4](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s4.png?raw=true)

5. After the app registration is completed, you will be redirected to the overview page of your app. Take note of the "Application (client) ID" as you will need it later to configure your application.

![Step 5](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s5.png?raw=true)

6. Search for "API Permissions".

![Step 6](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s6.png?raw=true)

7. Click on "Add Permission" Button.

![Step 7](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s7.png?raw=true)

8. Select "Microsoft Graph"

![Step 8](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s8.png?raw=true)

9. Choose "Delegated permissions" and navigate to "Files". 

![Step 9](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s9.png?raw=true)

10. check all the permissions that are required for your case as for accessing purposes Files.ReadWrite.All and Files.ReadWrite are checked.

![Step 10](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s10.png?raw=true)

11. Search for "Authentication".

![Step 11](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s11.png?raw=true)

12. Enable the Access token in the Authentication tab to ignite your application with the power of authentication. Click "Save" to apply the changes.

![Step 12](https://github.com/Mr-MeerMoazzam/Access-Onedrive-Data-using-MS-Graph-API/blob/main/assets/s12.png?raw=true)
