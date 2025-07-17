so use git or anything to get the bots source code
then install the nessacary Depenthencies with 'npm install'

then go into 'node_modules' then search 'discord.js' then 'src' then 'structures then 'interfaces' and finally open InteractionResponses.js

go to Line 165 and change this '   if (typeof options !== 'string') {' to '   if (typeof options != 'string') {'



Now edit the .env file and open termianl and run the command 'npde --trace-warnings bot.js'
