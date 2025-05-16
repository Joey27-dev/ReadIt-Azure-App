# ReadIt App

## Overview
ReadIt is a simple catalog application built using .NET Core that allows users to browse and manage a catalog of items locally or deployed via Azure App Service. It supports browsing catalog items and can be extended to add, update, or delete entries. The app is developed using C# and .NET 8/9.

## Useful Links

- [.NET Core SDK Downloads](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- [Azure App Service Documentation](https://learn.microsoft.com/en-us/azure/app-service/)
- [GitHub Actions for Azure](https://learn.microsoft.com/en-us/azure/app-service/deploy-github-actions)

## Deployment on Azure App Service

- Go to the Deployment Centre in your Azure App Service instance.
- Connect your GitHub repository where this ReadIt app is stored.
- Configure the branch you want to deploy (usually `main` or `master`).
- Azure will create a GitHub Actions workflow to automatically build and deploy your app on each commit.
- Monitor the deployment status via Azure Portal.
- Take a screenshot of your deployment setup as required.

## Troubleshooting

If you get errors related to .NET SDK or runtime:

- Ensure you have the correct .NET SDK installed.
- If missing runtime, install the appropriate runtime version from [Microsoft .NET downloads](https://dotnet.microsoft.com/en-us/download).
- If Visual Studio Code does not recognize `dotnet` commands, restart VS Code after installing the SDK.
- For NuGet package errors on Windows, try:
  - Delete `nuget.config` from `%appdata%\NuGet`
  - Restart Visual Studio Code
- For Azure deployment issues, check your GitHub permissions and Azure subscription settings.

## Contact Author

**Joash Austin Pillay**  
[LinkedIn - Joash Pillay](https://www.linkedin.com/in/joashpillay) • [GitHub: Joey27-dev](https://github.com/Joey27-dev) • [Email: joashaustinpillay27@gmail.com](joashaustinpillay27@gmail.com)

---
