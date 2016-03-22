# Bootstrap Web App
An empty app to start your new web app!

How to create a new sails app from this repository:
# Get the Code
- Download the .zip file from this repository (top right button)
- Extract the files (double click the .zip file)
- Rename the exctracted directory (should be called `bootstrap-master`) to your new project's name
- Copy the new project directory to your `code` directory

# Reinstall all node modules
- Open Node.js command prompt (windows) or the terminal (mac)
- Enter into your projet's directory (windows: `cd \code\project_name` | mac: `cd ~/code/project_name`) 
- Reinstall node modules `npm install` (this might take a while)
- Run the app `sails lift`
- Open Chrome and navigate to localhost:1337 to see the app
 
# Connect to a Git Repository
- Open the `helloworld` folder in Visual Studio Code (if not already open)
- Click on the Git icon (third from the top on the left)
- Click `Initialize Git Repository` (if the button appears)
- Write a commit message and click the checkmark icon
- Go to [GitHub](http://github.com), login and create a new repository
- In the setup screen, copy the bottom two lines (under "..or push an existing repository from the command line")
- In the command prompt, in your app directory, paste these lines and click [Enter]
- In windows, paste this line as well `git config --global credential.helper wincred`
- In Visual Studio Code, in the Git section, click on the three dots (top left) and choose `Publish` or `Sync` (whichever's available)
- Go back to the repository on [GitHub](http://github.com), and make sure that the repository exists with all the code

# Connect to Heroku
- Login to [Heroku](http://heroku.com)
- Click '+' to create a new app (in the top right corner)
- Give it a unique name
- In the 'Deploy' tab, connect it to your GitHub repository
- Click [Enable Automatic Deploys]
- Go to Manual Deploy and click [Deploy Branch]
- Wait for the deploy to finish and click [View App]

# Hooray! You can now start coding your real app!
