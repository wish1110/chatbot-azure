# chatbot-azure-deployment
This project shows how to deploy an echo-chatbot app to the Azure cloud

## Getting Started

### Prerequisites
1. App ready. In this project, the app is called "echo-bot" from the github https://learn.microsoft.com/en-us/azure/bot-service/provision-and-publish-a-bot?view=azure-bot-service-4.0&tabs=multitenant%2Cpython
2. Azure account ready.
3. 

### Executing program
either in azure cli or visual studio command line
1. az login
2. az webapp deploy --resource-group lauchunkit20001110-rg --name thisismyapp2024 --src-path C:/bot-deploy.zip --type zip

If your app is deployed successfully, you should see this
"
Initiating deployment
Deploying from local path: C:/bot-deploy.zip
Polling the status of sync deployment. Start Time: 2024-01-20 12:20:07.889707+00:00 UTC
Deployment has completed successfully
You can visit your app at: http://<your app name>.azurewebsites.net
"
### Help
Any advice for common problems or issues.
1. Apply log stream for monitoring. Either in CLI or Azure app service
2. Edit the config.py in your folder with your ID and key_value of your Microsoft Azure account
3. Set up the start-up program in the app service, general setting tab. link:https://learn.microsoft.com/en-us/azure/developer/python/configure-python-web-app-on-app-service

