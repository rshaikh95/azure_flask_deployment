# azure_flask_deployment
# Setting up Flask Application
## To start, I opened up Google Shell and GitHub. I created a new public repo called azure flask deployment. I opened up this repo on Google Shell and created a new file called app.py.
## I imported flask and pandas onto this new file. I created an app variable with the same name as the initial file and routed it to 2 html files. 
## I created an html file called base which was the home page that displayed my healthcare app with a head, body and footer detailing information on the webpage. the same was done for the about page. Then I created a html file for the dataset which loaded the dataset onto the webpage from app.py using pd.read

# Deploying to Azure Web Services
## I then deployed app.py via Azure. I first installed azure into google shell using a specific command. I then tested it out and began to log in using a device code. I then got into my student subscription via commands az account list and set. 
## I created a new resource group on Azure and matched it onto the shell via az webapp up and inserting my resource group name, app name, runtime and sku. After loading on the shell I checked Azure to see of it showed on the web services page. Finally I terminated the webapp at the end

# rahilazurerg.azurewebsites.net
