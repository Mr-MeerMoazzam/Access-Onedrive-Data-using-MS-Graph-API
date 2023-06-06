To sign up for Azure App using GitHub as your authentication provider, follow these step-by-step instructions:

1. Go to the Azure portal: https://portal.azure.com/ and sign in with your Azure account credentials.
2. In the search bar, type "App registrations" and select "App registrations" from the suggestions.
3. Click on the "New registration" button to create a new app registration.
4. Provide a name for your app registration, such as "TestingApp". Under the "Supported account types" section, choose the appropriate option based on your requirements. In the "Redirect URI" section, select "Web" as the type and enter the redirect URL for your application. This is the URL where users will be redirected after authenticating with GitHub. For local development, you can use "http://localhost:3000" or any other URL that matches your application's requirements. Once you have provided all the necessary information, click on the "Register" button to create the app registration.
5. After the app registration is completed, you will be redirected to the overview page of your app. Take note of the "Application (client) ID" as you will need it later to configure your application.
6. Search for "API Permissions"
7. CLick on "Add Permission" Button and Select "Microsoft Graph".
8. Choose Delegated permission.
9. Navigate "Files" and check all the permissions that are required for your case as for accessing purposes Files.ReadWrite.All and Files.ReadWrite are checked.
10. Ignite your application with the power of authentication by enabling the Access token in the Authentication tab. Simply click "Save" and unleash the endless possibilities!
