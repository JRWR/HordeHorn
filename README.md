## Author Summary

It's NodeJS, Install it, do things with it, this code is just really slap dashed together

if you want to do other things, try IFTTT and the blink.sh script that is called. you can use curl for that.

You will need to extract your Discord Token out of your local Storage on your brower and add it into horn.js

Copy the channel-id of #pings (right-click on the channel) 

past that, google is your best friend, if someone wants to update this pull requests are welcome!



## Installation:

__**Must be installed on a linux environment**__

##### First, install NodeJS on your local machine:
https://nodejs.org/en/download/package-manager/


##### Clone Repository to your local machine:

```
git clone https://github.com/JRWR/HordeHorn.git
```

##### Get discord token from your browser:

- Login to discord via the chrome browser
- Press F12 > Application > Local Storage > https://discordapp.com
- Find the Key `token` and copy the `value`
- Paste value to `client.login('XXXXXXXXXXXXXXXXXXXXX');`

##### Enable Developer mode in discord:
User settings > Appearance > Developer Mode

##### Get channel id(Must be in discord dev mode):
- Right click channel name > Copy ID
- paste ID to `var channelid='xxxx'`

##### Install project:
In the directory you downloaded the project, run this in the commandline:
`npm install`

Alternatively, run the following line to install all dependencies necessary:
`npm install nodemon`

Run application:
`node horn.js`

If you recieve an error regarding `Error: spawn mpg123 ENOENT`, make sure to install mph123:

Install mpg:
https://www.npmjs.com/package/mpg123
