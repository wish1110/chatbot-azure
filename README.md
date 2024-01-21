# chatbot-azure

Project Title
This project show how to deploy a echo-chatbot app to azure cloud

Description
An in-depth paragraph about your project and overview of use.

Getting Started
Dependencies
Describe any prerequisites, libraries, OS version, etc., needed before installing program.
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
Any advise for common problems or issues.
apply log stream for monitoring. Either in cli or azure app service
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
