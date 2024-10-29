# Pushbullet 'Push URL' Bookmarklet

## Overview

This bookmarklet provides a quick way to send the current page's URL to a predefined device using Pushbullet. When clicked, it instantly sends the link to the specified device, offering a simple way to share links without needing to manually open other apps or services.

## Features

- **One-Click URL Sharing**: Instantly sends the current URL to a pre-configured device using the Pushbullet API.
- **User-Friendly Notifications**: Displays unobtrusive visual feedback about the status of the request (sending, success, or failure).
- **Smooth Integration**: Works seamlessly in any browser that supports bookmarklets, with a straightforward setup.

## How to Use

1. **Create a new bookmark** in your web browser's bookmarks bar.
2. **Obtain your Pushbullet API Token**: Go to [Pushbullet Account Settings](https://www.pushbullet.com/#settings/account) to retrieve your API access token.
3. **Obtain Your Device Identifier**: Visit [Pushbullet Devices](https://www.pushbullet.com/#devices), click on your target device, and note the identifier string from the URL.
4. **Edit the Bookmark URL**: Paste the entire JavaScript code provided above in `pushbullet-bookmarklet.js`, replacing `APICODE` and `DEVICECODE` with your API token and device identifier, respectively.
5. **Save the Bookmark**: Rename it to something descriptive, such as **"Send to Pushbullet"**.
6. **Use the Bookmarklet**: Click the bookmark whenever you want to send the current page's URL to your device.

## Security Note

Ensure your Pushbullet access token remains secure. Bookmarklets are executed in the context of your browser and could expose sensitive data if used on insecure websites.

This code uses the Pushbullet API and requires you to use your personal API token and device ID. Handle these credentials with care to avoid unauthorized access.

---

Feel free to use and modify this script for personal use. If you encounter any issues or need further customization, reach out via GitHub.
