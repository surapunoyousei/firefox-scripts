## userChromeJS

Firefox 58.0b6 (current Developer Edition)

1. Save [config.js](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/installation-folder/config.js) to Firefox installation folder (usually **C:\Program Files (x86)\Mozilla Firefox**), next to **firefox.exe**.

2. Save [config-prefs.js](https://raw.githubusercontent.com/xiaoxiaoflood/firefox-scripts/master/installation-folder/config-prefs.js) to **\defaults\pref** inside Firefox installation folder (usually **C:\Program Files (x86)\Mozilla Firefox\defaults\pref**), next to **channel-prefs.js**.

3. Create **chrome** folder inside your Firefox profile. To open profile folder, visit the page **about:support** in Firefox, then click **Open Folder**.

4. Create **utils** folder inside **chrome**, then save all [these](https://github.com/xiaoxiaoflood/firefox-scripts/tree/master/chrome/utils) files to it.

5. Save [userChrome.js](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/chrome/userChrome.js) to **chrome**.

6. Save the desired [userChromeJS scripts](https://github.com/xiaoxiaoflood/firefox-scripts/tree/master/chrome) to **chrome** folder, especially [rebuild_userChrome.uc.js](https://github.com/xiaoxiaoflood/firefox-scripts/blob/master/chrome/rebuild_userChrome.uc.js) (userChromeJS Manager with Greasemonkey-like button menu).

7. Restart Firefox.
