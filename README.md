# Ideas
## IP bot
* The basic idea of this bot is to have something related with the user/client IP address.
* This bot should get a IP address easily for any user you’re talking to on FB/telegram/whatsapp etc
* Basic idea can be to just send a link to a user that gets the IP 
* Advanced would be sending something which doesn’t raise suspicion.

## XML to XSD convertor
* As the name suggests a tool that takes an XML file or multiple XML files and produce a XSD i.e schema for them.
* It would be nice if you can stick to python since there is no such tool in python and shit ton of them in java.

## AKTU
* This is very raw idea 
* Something related to aktu websites / results
* Basically aktu website sucks 
* Finding some particular circular or old exam papers takes is really tough 
* Scrape the shit out of it
* The problem is what will it be a website or a CLI/GUI tool ?
* Must be something everyone can use 
* Yes a website 
* Doesn’t have to be big, could be setup on gh-pages
* It can also be related to the results 
* Show results for all the roll no.
* Or between any two specific roll no.
* Will have to verify if the roll no is valid or not
* Will have to handle reCAPTCHA on (https://erp.aktu.ac.in/WebPages/OneView/OneView.aspx)
* Scrape only what matters
* If for single roll no then hell yeah everything
* If for multiple than only important stuff

## Show git status of multiple repositories
* For people who have lots of local git repository  and want to visualize it
* Could be an @ncurses interface or full @gui (maybe using @pyqt)
* Use @libgit2 bindings, such as: (https://github.com/libgit2/pygit2)
* Something like: Gitup

## Online ranger
* So ranger is a crazy good tool
* The whole idea is to provide this tool a link for a github repo and than operate over it just like in ranger
* I am not sure whether or not it is possible
* Let me(@mzfr) know if this isn’t possible
* Having it as simple CLI tool would be amazing
* You can also think of making a GUI but this would be a better CLI tool
* Problem that may arise
* This is not possible :)
* Providing a link mean you’ll have to download the whole repository
* If not downloading than requesting everytime would just make everything  slow
* Could use a DB to store an information about a particular repository 
* Handling DB will be hard plus it will be a shit storm when the size will increase
* Provide a link to file when someone want to see the content of the file.

## Profiling from chats
* Given a chat between any two people find interesting information from it.
* Create their profile like age and stuff
* This will be easy to do once you figure out what all do you want from it.
* Like any numbers shared. Could be mobile number or SSN or aadhar number etc
* Emails or any other contact info
* Check language if it’s not english.
* Lookout for hinglish(english + hindi)
* If images/ links/ videos are present than viola
* High level stuff  would be if you can use some analysis to know what image/video/link is
* Lookout for any 18+ words :)
* A good GUI would be nice 
* Website ?
* Accept all kind of chats like FB/whatsapp/telegram
* This shouldn’t affect you though

## Web based interface for youtube-dl
* Pass link to the video along with some filter and boom
* Filters could be similar to options in CLI tool
* Just in case you were living under a rock and had no clue what is youtube-dl: 
* As the name suggest it’s a CLI tool for downloading youtube videos
* (https://rg3.github.io/youtube-dl/)

## CLI tool for TED talks
* Grab videos from TED.com (https://www.ted.com/talks)
* Options should be something similar to youtube-dl
* Or could be just few options so it isn’t very complicated
* Also locally perform some operation on those videos
* Auto-rename
* Download subtitle
* Filter options like speaker, date etc
* All these options can also be used while downloading 

## CLI/Website to list all GCI or BOSS task
* It would be nice if we can easily list down all the google code in(GCI) and Bountiful Open Source Summer(BOSS) tags
* Basically for GCI and BOSS issues in specific repositories are marked with tags like GCI or BOSS.-
* Finding them is not hard but it would be nice to list them at on place
* This whole thing could also be designed to find issues marked with some tags on particular repos
* This will give this tool a whole new image
* A lots of API calls will be required but should be done by API and not by scraping
* CLI/ website both could be nice
* Website will have a upper hand since providing links will be more easy
* Also if we are making website than we can display content of the issue (maybe)
* CLI tool can also be good

## Lichess challenges (cron job)
* Setup a cron job that will keep an eye on lichess challenges and reports you
* This will have to work with the filter because those challenges changes with eye blink
* It should report back a challenge link and nothing else
* Will have to setup a cron job for this.
* A web service can also be good but tough to manage(I guess)
* This totally depends on how you get those challenges (will be tough without bot account)
* Currently there is no lichess API endpoint for challenges hopefully we’ll get something
* I have opened an issue on ornicar/lila 

## Visualize followers/followings
* So there was a new endpoint added to lichess API: (https://lichess.org/api#tag/Relations)
* This can be utilised to visually represent someone’s followers/followings
* Graphically show the ratings of all the follower
* Show all the person they are following
* Difference between their ELO ?
* Common followers/followings of two users
* Lot can be done with this if done correctly.
* For easy-ness do it in Ipython notebook
* For crazy fun make a website
* Only do that when you have a clear picture of what all can you do in it.


