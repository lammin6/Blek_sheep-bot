# How to Set Up Music Bot

Create a Bot on the [Developer Portal](https://discord.com/developers/applications) on Discord and make an application and create the name and description for the bot.


Then, create a bot!
![alt text](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/musicbot.png)

Then, Invite the Bot to your server using the client ID and the [Discord Permissions Calculator](https://discordapi.com/permissions.html)!


Then, sign up for Heroku to Make the bot 24/7!


[Heroku Website](https://id.heroku.com/login)


![alt text](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/music%20bot.png)


After that, Fork this Discord Music Bot Project!
![alt text](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/forkingimage.png)


Then, Download the Zip File and Make a new Repository, and make it **PRIVATE**
![alt text](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/downloadzip.png)

Then, go to the config.js file, and put your Discord Token, and make sure to put all intents!
![alt](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/botintents.png)
![alt](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/bottoken.png)


Afterwards, go back to Heroku, remember the name of the Repository you just made, because you will put it in the box after it asks in Heroku. Like in the image below
![ois](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/connectingrepo.png)


Then, scroll down, enable automatic deploys and deploy the branch! Your bot should be working, but if you want it to be **24/7** follow the further instructions
![hsd](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/deployrepo.png)


# How to Make the Bot 24/7


After that finishes, go into overview, and click configure dynos!
![ashfdjk](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/configure-dyno.png)


Then, turn on *worker- node.js* and wait 2 minutes before turning off *web- npm start*
![dhos](https://github.com/RealMaoMao/Discord-Music-Bot/blob/main/commands/dynos.png)

And that, my friends is how to make a Discord Music Bot in 6 minutes!
