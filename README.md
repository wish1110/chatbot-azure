## chatbot-azure
This project shows how to deploy an echo-chatbot app to the Azure cloud

# Getting Started
Dependencies
Prerequisites
1. App ready. In this project, the app is called "echo-bot" from the github
2. Azure account ready.
3. 
ex. Windows 10
Installing
How/where to download your program
Any modifications needed to be made to files/folders
Executing program
az login
az webapp deploy --resource-group lauchunkit20001110-rg --name thisismyapp2024 --src-path C:/bot-deploy.zip --type zip

If your app is deployed successfully, you should see this
"
Initiating deployment
Deploying from local path: C:/bot-deploy.zip
Polling the status of sync deployment. Start Time: 2024-01-20 12:20:07.889707+00:00 UTC
Deployment has completed successfully
You can visit your app at: http://<your app name>.azurewebsites.net
"
Help
Any advice for common problems or issues.
1. Apply log stream for monitoring. Either in CLI or Azure app service
2. Edit the config.py in your folder with your ID and key_value of your Microsoft Azure account
3. Set up the start-up program in the app service, general setting tab. link:https://learn.microsoft.com/en-us/azure/developer/python/configure-python-web-app-on-app-service
command to run if program contains helper info
Authors
Contributors names and contact info

ex. Dominique Pizzie
ex. @DomPizzie

Version History
0.2
Various bug fixes and optimizations
See commit change or See release history
0.1
Initial Release
License
This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

Acknowledgments
Inspiration, code snippets, etc.

awesome-readme
PurpleBooth
dbader
zenorocha
fvcproductions
