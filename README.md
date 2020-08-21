# How to create and deploy nodejs/express web app on azure in few steps

1 
npm install express-generator -g

2 create an express sample application:
express newappname

3 cd newappname
   change directory:
     > cd newapp

   install dependencies:
     > npm install

   run the app:
     > SET DEBUG=newapp:* & npm start
4  git init & commit

5  Azure portal - Azure deployment center - CI/CD 
   choose local git or github

6  in vs code - azure app service
   deploy to related app 
   <br />
   refer to
   <br />
   https://docs.microsoft.com/en-us/azure/app-service/quickstart-nodejs?pivots=platform-windows
   https://thewebspark.com/2018/04/18/creating-and-deploying-express-web-app-on-azure-in-few-steps/
