#Fembot

Fembot is a song request bot for twitch.tv through spotify. This is currently a very new release with lots of bugs. Currently the play list is not setup to reflect the propper songs at all. 

#Issues
  - Must refresh playlist (by that i mean change to another screen in spotify or playlist) If playlist isn't refreshed songs are not updated. 
  - Songs are not auto deleted. Stay on top of it between streemes.

#Know Bugs
  - songs that has weird foriegn symbols from another language or weird charcaters [] may or may not crash the bot.
  - !songlist will show a playlist that is not yours. Ignore this your true playlist is in your spotify account. (will be fixed in the future)
  - The !commands list is totally broken and will not reflect any of your commands. They are hard coded at the moment to show another channels. (Sorry for the inconvenience)

#Setup Instructions
  - Unzip contents to some location
  - Run app.exe allow permissions if windows firewall asks you
  - #Required
     - A twitch account dedicated to the bot that is not your primary one. For example I have access to the twitch account chinnbot
     - The oAuth token for that account. (Must be logged into that account when getting the oAuth token) You can get this token here http://twitchapps.com/tmi/ include the whole oauth include the oauth:
     - Your bot username needs to be a mod in your channel for all commands to function properly
     - The channel name you wish your bot to join. For example my channel name is blackmarmalade (all lower case always)
     - A spotify premium account to use song spotify portion of the playlist
     - A private spotify playlist
     - The ID to your private spotify playlist (Click the orange links on the webpage if you need help finding this information)
     - Your spotify username (Click the orange links on the webpage if you need help finding this information.)

#Running The Bot
  - MAKE SURE SHUFFLE IS OFF ON SPOTIFY
  - Once the bot is running you should see a black command prompt window. Leave this open while you run the bot. It will also open a web page on your local host on port 5000 127.0.0.1:5000 if you ever wish to acess the settings again. Once you have configured the settings and connected the bot you can close this browser window.
  - Take notice before you close the web browser that you bot is connected. To do so look the button on the settings page it should say dissconnect bot if you are connected. Also there should be green text that says the bot is connected. Note that you must authorize spotify the spotify page before connecting the bot. The bot will reset every time you close the black command prompt window.

#Commands
  - #Mod Only Commands
      - !sron (turns song request on can also be done on the wesbite but disconnects the bot)
      - !sroff (turns song request off can also be done on the wesbite but disconnects the bot)
      - !gameq on "a queue for people that want to play with you off by default"
      - !gameq off
      - clearq "clears the entire queue"
      - !next 5 "clears the next 5 people or however many peole out of the queue."
      - !addcom "example !addcom_user | !hello | hello world
  - #Commands for Everyone
    -  !dicksize
    -  !roulette
    -  magic eight ball,
    -  gg
    -  !sr "Spotify URI, URL, ID, title - artist, very few youtube ID's"
    -  !songrequest "Same thing as above"
    -  !uptime
    -  !quote "Displays a random quote"
    -  !join "joins the active player queue"
    -  !commands (broken) will not show your propper commands

