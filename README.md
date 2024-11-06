# 307-proj-1


## Contributing
### Coding Standards:
    1. Utilizing the Prettier Code Formatter on VS Code
    2. Camel case for functions and variables
    3. Pascal case for react components

## connecting to mongodb with .env
git pull to make sure you have the most recent updates, then in the backend branch in the backend folder create a .env file. everyone should have their own .env file. in the .env file you're gonna put in your MONGODB_URI, which you get in step 3 as later described which you get this from the cloud.mongodb website. in the website in the overview page where it says 'clusters' click on connect then 'drivers' and follow the instructions on there, there are 3 instructions, the first one that is autogenerated is fine, so ignore it. the second step is "run npm install mongodb" in the root backend, so the SLOutions root folder. the third step will give you the MONGODB_URI link 

mongodb+srv://<username>:<db_password>@sloutions.jsptt.mongodb.net/?retryWrites=true&w=majority&appName=SLOutions

the only thing in the .env file should be your mongodb_uri = 'link' without the '' as shown above. replace the <username> and <db_password> with your username and your password without the <>. then navigate to the node.js that i have already created and in line 15 there are instructions on how to add your credentials. once you add your credentials to your .env and have done the node.js, in terminal cd to backend (folder) then run node node.js and it should say "Connected to mongoDB Atlas Pinged your deployment. You successfully connected to MongoDB!"

