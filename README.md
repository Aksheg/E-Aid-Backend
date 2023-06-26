# NODE-Live-Project
# Yarn start to run your server at development
# To run prettier, run yarn pretty. This is going to format all your files for your project

# Run yarn lint to help to locate your errors with eslint configuration

# The database is configured in the model directory at db.model and imported back to the app where it runs

#SMTP with GMAIL and BREVO(sendinblue) configured and the configuration file is in index.conf in config directory. A way to implement has been added and tested in index.ts router in the router. 

#Email with the name eaidcustomerservice@gmail.com has been added and tested

#password for it is included in the dotenv file as DB_PASSWORD

#The port runs on 5000


# How to push 
git pull origin develop
- Branch out develop to create new branch - git checkout -b your-branch-name
- write your code
-you git add .
- you git commit -m"type your commit message here"
- git pull origin develop (updates your branch with develop)

After resolving conflicts,
- git push origin your-branch-name
- Then go to github and raise a Pull Request(PR)