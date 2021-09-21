# compact-firefox
Compact UI mod for Firefox. Ironically, created *before* the new UI, because I didn't realize Firefox actually *came with* a compact UI option by default at the time.

## Instructions:

1. Go to **about:config**, then search for **toolkit.legacyUserProfileCustomizations.stylesheets**. Set that variable to **true**. 
2.  Go to **about:profiles**. Look for the profile that has "**This is the profile in use and it cannot be deleted.**" above it. Go to the entry that says "**Root Directory**", then click the "**Open Directory**" button to the right of the text. Open or create the folder "chrome", then drag and drop userChrome.css into the folder. 
3.  Restart the browser.

You're done! The UI should be changed now.
