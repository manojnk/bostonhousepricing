### Bostonhousepricing
### Software and tools requirement

1. [Github Account](https://github.com/)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Heroku Account](https://dashboard.heroku.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new Environment
***
conda create -p venv python==3.7 -y
***
shows an error H000 then 
***
conda config --set ssl_verify false
***
after that run the create new environment line
and then set back ssl_verify back to true
***
conda config --set ssl_verify True
***
To setup required laibraries
***
pip install -r requirement.txt
***
TO config user name and emailID (linked with github)
***
git config --global user.name "name"
git config --globaluser.email "email"
***
git add and get status
***
git add .
git status
***
to commit code
***
git commit -m " this commit includes requirement and readme file"
***
git push
***
git push <remote> <branch>
git push origin main
***



