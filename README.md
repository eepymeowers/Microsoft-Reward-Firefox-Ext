[![CodeFactor](https://www.codefactor.io/repository/github/tmxkn1/microsoft-reward-chrome-ext/badge)](https://www.codefactor.io/repository/github/tmxkn1/microsoft-reward-chrome-ext)

# Microsoft Rewards Bot

A Firefox extension for Microsoft Rewards, which automatically clears PC, mobile and Edge search quests and displays daily point countdown.

This extension will not clear any promotional link or quiz quests and this feature will not be implemented.

**This is a bot!**

Use at your own risk. I do not take responsibility for any consequence caused by this extension.

### Note: This is a port of a Chrome extension originally made by tmxkn1.

# Install from GitHub

1. Head to [Release](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/releases) and download the XPI for the version you want.

# Use

1. Log into [Microsoft Rewards](https://account.microsoft.com/rewards) and [Bing](https://www.bing.com/).
2. Enjoy.

*Note: You may need to repeat step 1 every time you restart Firefox.*

# Functionality

### Background Work

The extension checks your daily Microsoft Rewards progress every two hours and clears any incomplete search quests. When you have any available quiz/link quests yet to complete, a yellow badge will show with a number indicating the amount of points they worth.

### Action Button

1. A button to force check reward progress.
2. A link to Microsoft Rewards.
3. Options:
   1. Compatibility Mode. Toggle to enable/disable a different way of calculating point countdown. Try this if you have any issues with the current point countdown method.
   2. Copy Debug Info. This will place a bunch of information in your clipboard. The information is not useful for end users.

### Action Button Badge

The colour of the badge changes depending on your daily reward progress or the status of the extension:

![greyLogo](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/blob/master/src/img/grey@1x.png?raw=true) - Just hang on a second. The extension will start to work soon.

![blueLogo](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/blob/master/src/img/busy@1x.png?raw=true) - Working hard on doing those search quests for ya!

![greenLogo](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/blob/master/src/img/done@1x.png?raw=true) - Congratulations! You have completed all quests for today.

![yellowLogo](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/blob/master/src/img/warn@1x.png?raw=true) - Attention! You still have some points to earn through quests.

![redLogo](https://github.com/eepymeowers/Microsoft-Reward-Firefox-Ext/blob/master/src/img/err@1x.png?raw=true) - Oops... an error occurred - Check out [Troubleshooting](TROUBLESHOOTING.md).


# Credit
### tmxkn1 - [The Chrome extension.](https://github.com/tmxkn1/Microsoft-Reward-Chrome-Ext)
