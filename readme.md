# theDrizzlyBearDOJO - First Steps

> You can find the Files and Installatoin Guide here : https://github.com/stereoIII6/theDrizzlyBearDOJO  

## First look around 

> The root dir ... includes the entire project including backend

![image](https://ipfs.io/ipfs/QmaAGUG5ioEwLMPwAShpXyE7YtawNhEZEa7vP7VKccZCQh?filename=root_dir.png)

In the project directory we have 2 file to keep in mind ```tuffle-config.js``` and ```package.json```
in the truffle configuration file we can edit our network settings and contract settings. The package 
file is a node configuration file that shows all backend dependencies. We should see ./app , ./contracts,
./migrations and ./test directories in our project folder. The ./node_modules Folder we are going to ignore
for now.


> The app dir ... everything inside is taking care of the client side 

![image](https://ipfs.io/ipfs/QmaAGUG5ioEwLMPwAShpXyE7YtawNhEZEa7vP7VKccZCQh?filename=root_dir.png)

Inside ./app we find the ```drizzleOptions.js``` file it configures our connection to web3 truffle and 
our frontend and always keeps the state of our frontend website up to date. Another ```package.json``` 
node configuration file shows all the frontend dependencies. We should see a ./public and a./src folder 
here. The ./public holds only the static html part of your project while ./src holds all the important 
frontend files.

> ./app/src is the actual project directory it contains all frontend project files, contract references
and react components.

> The contracts dir ... the solidity codebase

Inside the ./contracts folder we store all our Smart Contracts written in Solidity. These Contracts represent 
the code that is actually being saved on the blockchain as usable functions permanently !

> The migrations dir ... put it on the chain 

The migrations directory takes care of migrating the contracts onto the blockchain and compiling .json 
references of them into your ./app/src/contracts folder so your frontend can interpret them properly !

> The test dir ... is kind of self explanatory but actually quite complicated to use correctly so rather 
a topic for a more advanced lesson


# The DrizzlyBears Workflow


