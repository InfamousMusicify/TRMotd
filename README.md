# TRMotd
Truly Random Message of the Day

     A Datapack for Minecraft Java Edition
     which sends a random message to the player when they log in.
     (Compatible with 1.14+ - 1.15+)

     Version 4.4 or higher Recommended.
     
     Motd Sources: All the Minecraft Splashes as of Dec 2019, an evergrowing # of 2b2t Motds, Ubuntu 2007 Forums Motds,
     And a fair amount of custom Motds.

     You can use the command "scoreboard players set @p Logout 1" to trigger a message for the closest player,
     or "scoreboard players set @a[distance=..50] Logout 1" for an area of effect message.

     If your going to use this on a public or busy server I recommend editing some of the messages,

     To change the messages themselves, 
     navigate in the data/rmt/functions/join.mcfunction file and edit the text in between the brackets.
     Example:
     {"text":"Change this to your message","color":"gold"}
     
     There are notes in the datapack .mcf files on how to add more messages

     4 Commands, /trigger <motd|stoprecord|rfxON|rfxOFF>
     motd: sends the player a random message
     stoprecord: stops the music that plays.
     rfxON: Turn on Effects for yourself.
     rfxOFF: Turn off Effects for yourself.


     I spent an inordinate amount of time making this so, I really hope your enjoy. :)
     Special Thanks to M.R. Programs for helping me create this.
     and to mcskware for his prng datapack for 1.13 and willingness to share his code.

     TRMotd (aka RMotd, Random Motd datapack)

     Cheers 
     -Infamous 
