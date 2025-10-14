# locked-mode-bug
This is a bug with Google Forms Locked Mode that lets you exit Locked Mode without actually exiting the form itself. It works on ChromeOS version 139 and has been functional since at least version 131. There’s a good chance it works on all ChromeOS versions that support Locked Mode.

# Instructions:
- Open two windows of the locked form in question. Ensure you can view both forms without needing to switch tabs.
- Click the Continue button on both pages at the *exact* same time. If you are too late, it will lock you as normal.
>This exploit is likely possible on touchscreen Chromebooks only due to how fast you need to be to click both buttons.
- You should be in locked mode now, but it will only show a blank window with a forms icon at the top left. Click it.
- It should now show the enter locked mode screen on the form when you're already in locked mode. Click Continue.
- Click the overview button on your keyboard. You'll be able to see all the windows, and hence "exit" locked mode. However, you can still return to the form and complete it.

# Notes:
- I reported this to Google, but they declined to make a fix. If you try this, you do so at your own risk; I accept no responsibility for any consequences.
- You might notice that locked mode is an app called Assessment Assistant (https://chromewebstore.google.com/detail/assessment-assistant-dev/ibnfdimnablpmgpmgegnbdadookdffie).
- Alt-tab closes the quiz - use the window view button!
- You cannot screenshot until you complete/exit the form properly ('submit' or 'close quiz')!

You can practice this glitch by creating your own locked mode form, publishing it, and copying its link.
It used to be easier when previewing a locked mode form behaved like the real locked mode.

## Note: There are better Locked Mode Bypasses in https://github.com/S-PScripts/chromebook-utilities/
