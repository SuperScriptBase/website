---
title: "Mac iOS Commands"
date: 2022-12-08T14:06:23-07:00
toc: false
images:
tags: ["posts","mac"]
---

1. Open Spotlight Search - command key + spacebar
2. Say command - ❯ say hello world
3. Show wifi passwords - ❯ security find-generic-password -wa wifiname > password
4. Show wifi passwords + copy ❯ security find-generic-password -wa wifiname | pbcopy (copy and share)
    1. After running use command to paste save or email - command + v
5. command+option+shift+v - will paste with out formatting (plain text)
6. command+v - will paste to share
7. Type - caffeinate -- prevent the system from sleeping on behalf of a utility
8. Screen Capture - command+shift+3 - whole screen
9. Screen Capture - command+shift_4 - selected area
10. Screen Capture - command+control+shift+4 - copies to clipboard
11. Screen Capture Name File - defaults write com.applescreencapture name “RENAME”
12. Screen Capture Name File Type - defaults write com.applescreencapture type  jpg
13. Screen Capture Name File Type - defaults write com.applescreencapture location ~/Desktop/screenshots
14. See that all has been downloaded - sqlite3 ~/Library/Preferences/com.apple.LaunchServices.QuarantineEventsV* 'select LSQuarantineDataURLString from LSQuarantineEvent'
15. Change Password - passwd