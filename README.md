# placebot

**WARNING: ONLY REDDIT ACCOUNTS WITH VERIFIED EMAIL ARE SUPPORTED.** If your account has a 20 minutes rate limit, this will probably work, but will send more requests than necessary.

## How to use

- Use a chromium based browser
- Log in to reddit
- Go to your extension page (chrome://extensions/)
- Load the unpacked extension. You might have to enable developer mode. The checkbox is in the right corner of the extension page
- If you see *service worker (inactive)*, click on it

![Extension unpacked demo](/assets/extension-unpacked-demo.png)

- This will open a console window that activate the extension that should look like this :

![Service worker demo](/assets/service-worker-demo.png)

- Go to https://reddit.com/r/place/. You should see something like this where you normally see the subreddit name :

![Reddit demo](/assets/reddit-demo.png)

- If you don't see the message above, press CTRL+F5 on your keyboard to refresh the page from the server

- Press CTRL+SHIFT+I or F12 on your keyboard to open up developer tools and click on the console tab. You should see something like this:

![Console demo](/assets/console-demo.png)

- You can now close the two developer tools windows

## Use multiple accounts

You can use multiple accounts by opening multiple browser windows in private mode.
