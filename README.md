# AzureADAuthenticationTest

This was a proof of concept for an ASP.NET Core Web App to understand how to implement authentication using Azure AD. 

The only changes that need to be made and that you can see in the code added to this repo are:

- Program.cs additions with appropriate nuget packages
- appsettings.json Azure AD information in regard to tenant and Azure AD app registration.

With these changes the authentication is hooked up and ready to go. 

To determine which pages require authentication or not, use:
- [Authorize]

or

- [AllowAanonymous]
