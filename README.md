# Idea List

This is a general idea list.

If you have some which you like to share with everyone then please feel free to open an issue.

-------------------------------------------------------------------------------
## IP bot

*   The basic idea of this bot is to have something related with the user/client IP address.
*   This bot should get a IP address easily for any user you're talking to on FB/telegram/whatsapp etc
*   Basic idea can be to just send a link to a user that gets the IP
    *   Advanced would be sending something which doesn't raise suspicion.

-------------------------------------------------------------------------------
## Interface to view @Github user's @activity @feed

*   It has now been removed from the website, but is still available via the @API and the @atom feed.
*   Having a @frontend for it in @react would be neat.
*    Something that people might actually use (if done right)
*   Is a nice starter project for @node, @js, @webpack etc.
*   Should try to imitate the old activities page as much as possible.


    + __Skill required__ : Node.js, webpack, react
    + __Difficulty__: Hard

    + __Features__:
        *   Should have @[pagination ](https://www.w3schools.com/howto/howto_css_pagination.asp)to display as much activity as possible
        *   Deal with rate limits: rate limits could be how much data is to be displayed or how many requests could be handled at much
        *   Filter feed by event type (similar to that @userscript)
        *   This means that it would be nice to filter things by searching all the star a person have given in a day/month/year
        *   Not just star but all the forks, follow, commits etc
        *   Work for user/org etc.
             - It should work for everything that can be on github i.e user or organisation
            - For org filters/activities will have to be handled according to the Github API
    + __Demo__ -
        + [Github-activity](http://caseyscarborough.com/github-activity/)
        + [Github-activity-feed](https://github.com/andrewhood125/github-activity-feed)
            + This ain't good cause no one want shit to build it up
            + Website is the key but we can take something from this :)

-------------------------------------------------------------------------------
## XML to XSD convertor

*   As the name suggests a tool that takes an XML file or multiple XML files and produce a XSD i.e schema for them.
*   It would be nice if you can stick to python since there is no such tool in python and shit ton of them in java.


    + __Skill required__: python 3, basic understanding of XML/XSD
    + __Difficulty__: Intermediate

    + __Features__ and requirements:
        *   Must be simple CLI tool
        *   Option to take a folder as an input then find all the XML files in it and produce XSD
        *   Schema validation must be present
            + Again this must take a single XSD and should be able to run on multiple XML at once

        *   Use [xmlschema](https://pypi.org/project/xmlschema/) for validation and stuff.

        *   Use tools like [Trang](http://www.thaiopensource.com/relaxng/trang.html) for xsd generation
            *   Trang is written in java so it's hard to use it in python script.
            *   Trang is just an example try to see how it works and handle it your way :)
            *   You can use website like [Freefromatter](https://www.freeformatter.com/xsd-generator.html) and then do some post scraping and stuff

-------------------------------------------------------------------------------
##  AKTU

*   This is very raw idea
*   Something related to aktu websites / results
*   Basically aktu website sucks
    *   Finding some particular circular or old exam papers takes is really tough
*   Scrape the shit out of it
*   The problem is what will it be a website or a CLI/GUI tool ?
    *   Must be something everyone can use
        *   Yes a website
            *   Doesn't have to be big, could be setup on [gh-pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)
*   It can also be related to the results
    *   Show results for all the roll no.
    *   Or between any two specific roll no.
        *   Will have to verify if the roll no is valid or not
        *   Will have to handle reCAPTCHA on [https://erp.aktu.ac.in/WebPages/OneView/OneView.aspx](https://erp.aktu.ac.in/WebPages/OneView/OneView.aspx)
        *   Scrape only what matters
            *   If for single roll no. then ,hell yeah everything
            *   If for multiple than only important stuff.

-------------------------------------------------------------------------------
## Show git status of multiple repositories

*   For people who have lots of local git repository  and want to visualize it
*   Could be an @ncurses interface or full @gui (maybe using @pyqt)
*   Use @libgit2 bindings, such as: [https://github.com/libgit2/pygit2](https://github.com/libgit2/pygit2)
*   Something like: [Gitup](http://gitup.co/)

    + __Skill required__: python, pyqt
    + __Difficulty__: Intermediate

-------------------------------------------------------------------------------
## Profiling from chats

*   Given a chat between any two people find interesting information from it.
    *   Create their profile like age and stuff
*   This will be easy to do once you figure out what all do you want from it.
    *   Like any numbers shared. Could be mobile number or SSN or aadhar number etc
    *   Emails or any other contact info
    *   Check language if it's not english.
        *   Lookout for hinglish(english + hindi)
    *   If images/ links/ videos are present than viola
        *   High level stuff  would be if you can use some analysis to know what image/video/link is
    *   Lookout for any 18+ words :)
*   A good GUI would be nice
    *   Website ?
*   Accept all kind of chats like FB/whatsapp/telegram
    *   This shouldn't affect you though

    + __Skill required__: Python, pyqt(for GUI), flask/django for website and other thing that I don't know

    + __Difficulty__: varies from easy to hard depending on how good you want the tool to be.

-------------------------------------------------------------------------------
## Web based interface for youtube-dl

*   Pass link to the video along with some filter and boom
*   Filters could be similar to options in CLI tool
*   Just in case you were living under a rock and had no clue what is youtube-dl:
    *   As the name suggest it's a CLI tool for downloading youtube videos
    *   [https://rg3.github.io/youtube-dl/](https://rg3.github.io/youtube-dl/)

    + __Skill required__: Python, flask, HTML, CSS

    + __Difficulty__: Beginner

-------------------------------------------------------------------------------
## CLI tool for TED talks

*   Grab videos from TED.com ([https://www.ted.com/talks](https://www.ted.com/talks))
    *   Options should be something similar to youtube-dl
    *   Or could be just few options so it isn't very complicated
*   Also locally perform some operation on those videos
    *   Auto-rename
    *   Download subtitle
    *   Filter options like speaker, date etc
    *   All these options can also be used while downloading

    + __Skill required__: python

    + __Difficulty__: Beginner

-------------------------------------------------------------------------------
## CLI/Website to list all GCI or BOSS task

*   It would be nice if we can easily list down all the google code in(GCI) and Bountiful Open Source Summer(BOSS) tags
*   Basically for GCI and BOSS issues in specific repositories are marked with tags like GCI or BOSS.
    *   Finding them is not hard but it would be nice to list them at on place
*    This whole thing could also be designed to find issues marked with some tags on particular repos
    *   This will give this tool a whole new image
*   A lots of API calls will be required but should be done by API and not by scraping
*   CLI/ website both could be nice
    *   Website will have a upper hand since providing links will be more easy
    *   Also if we are making website than we can display content of the issue (maybe)
    *   CLI tool can also be good

    + __Skill required__: python, flask(for website)

    + __Difficulty__: varies from beginner to intermediate

-------------------------------------------------------------------------------
## Lichess challenges (cron job)

*   Setup a cron job that will keep an eye on lichess challenges and reports you
    *   This will have to work with the filter because those challenges changes with eye blink
*   It should report back a challenge link and nothing else
*   Will have to setup a cron job for this.
    *   A web service can also be good but tough to manage(I guess)
*   This totally depends on how you get those challenges (will be tough without bot account)
    *   Currently there is no lichess API endpoint for challenges hopefully we'll get something
        *   I have opened an [issue](https://github.com/ornicar/lila/issues/4455) on ornicar/lila

-------------------------------------------------------------------------------
## Visualize followers/followings

*   So there was a new endpoint added to lichess API: [https://lichess.org/api#tag/Relations](https://lichess.org/api#tag/Relations)
*   This can be utilised to visually represent someone's followers/followings
    *   Graphically show the ratings of all the follower
    *   Show all the person they are following
    *   Difference between their ELO ?
    *   Common followers/followings of two users
    *   Lot can be done with this if done correctly.
*   For easy-ness do it in Ipython notebook
    *   For crazy fun make a website
        *   Only do that when you have a clear picture of what all can you do in it.

    + __Skill required__: python, flask(for website), Ipython notebook

    + __Difficulty__: varies from beginner to intermediate

-------------------------------------------------------------------------------
# **Tools you can contribute to**

*   **Pylama**
    *   https://github.com/klen/pylama#run-pylama-from-python-code
*   **Lichess-bot**
    *   https://github.com/careless25/lichess-bot/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc
*   **errbot **
    *   https://github.com/errbotio/errbot
*   **Smoke detector    **
    *    https://github.com/charcoal-se/smokedetector
    *   Don't go on it's name. Kinda cool repo to work on
*    **Yoda**
    *    https://github.com/yoda-pa/yoda
*    **slack-meme **
    *   https://github.com/nicolewhite/slack-meme

All of these repositories are beginner friendly. Just go for it

If you want to explore more repo or something that is not related to beloved python than go to - [Codetriage](https://www.codetriage.com/)
