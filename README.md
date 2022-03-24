# chat_App using nodejs and socket.io
Create a free account on Heroku
After completing all processes now login to your account.
Click on the “Create new app”.
Open the Deploy tab and scroll to the “Deployment method” section of the tab.
Select GitHub as a method. It will show a “Connect to GitHub” option where we add provide our GitHub repository. If you are doing it for the first time, Heroku will ask permission to access your GitHub account you have to permit that.Here, you can search for your GitHub repository and click connect for creating a connection.
After that, the Deployment section will show up where you can select pick them up and deploy or Manual Deployment, click Enable Automatic Deploys.
Now we have to tell Heroku that our app is a NodeJS app.
Open the Settings tab scroll down and click “Add buildpack”. 
Select NodeJS from the options and click Save changes. Now, go back to the Deploy tab, and click Deploy Branch at the bottom.
Heroku will take the code and host it. Open the Activity tab and there you can see the progress: 
![Screenshot (70)](https://user-images.githubusercontent.com/82281265/159940092-49f0a3a8-6dfb-400d-86f6-da9d500c07eb.png)
