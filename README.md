# CF-questions-extension

A chrome extension that shows your pending questions on Codeforces instead of posts in Facebook feed.Click any of them to open the problem page.

## Installation Instructions

The extention can be installed from [Chrome web store](https://chrome.google.com/webstore/detail/codeforces-wa-questions-f/ohjicmhfblgpmcbholdnnbjgamifmoli).
<br>
By default username is not set, installing it first time , you have to setup username  by clicking on options of the extension in the Chrome Extension Page. More description on this [Codeforces post](http://codeforces.com/blog/entry/20724)
<br><br>
If you would like to modify the extention (maybe add new functionality), you can clone the repo and make changes in the desired files. You can then load it directly by enabling Developer mode in `chrome://extensions/` and loading the unpacked extention directly from file system. 

## Small Description
It is using [Codeforces API](http://codeforces.com/api/help) for validating username and fetching the submissions.
Currently only first 1000 submissions are fetched.
<br>
**background.js** is used for making a secure http connection from https facebook page.
## TODO
- Correctly link Gym problems to their webpages. 
- Add a timer facility to remove feed after say 10 minutes of daily usage Or removing it after 2 minutes of refreshing the page.
- Port the extension to firefox.

## Attribution
The project is built on top of nealwu's [KillNewsFeed](https://github.com/nealwu/KillNewsFeed).
