# Facebook is so annoying

> Here's how you can get rid of annoying Facebook Ads.

1. First, make sure you're logged into Facebook and navigate to https://www.facebook.com/adpreferences/?section=interests
2. Click "See All Interests"
3. Open your browser's Javascript console (press F12)
4. Copy & Paste this script: `setInterval(function(){ document.querySelectorAll('div[aria-label="Remove"]')[0].click() }, 2000);`
5. Wait for all interests to be remove.

> 2000 = 2 seconds is the number of miliseconds to wait between clicking the "Remove" button.
