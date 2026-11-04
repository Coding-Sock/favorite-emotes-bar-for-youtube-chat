# Favorite Emotes Bar for YouTube Chat

Effective date: November 4th, 2026

This page explains how the Favorite Emotes Bar for YouTube Chat browser add-on handles information and describes its terms of use.

## Privacy & Data Use

### Information stored by the add-on

The add-on stores favorites and preferences in your browser’s extension storage. This may include:

- Global and channel-specific favorite emotes
- Custom emote shortcuts and associated image URLs
- The custom-emote allowlist
- Display preferences, such as toolbar size and visibility settings

Global favorites, the allowlist, and display preferences use browser sync storage when it is available. If browser sync is enabled, your browser provider may sync these settings across your devices, subject to that provider’s settings and privacy policy.

Channel-specific favorites are stored locally in your browser and are not automatically synced between devices.

### Information processed on YouTube

The add-on runs on YouTube live chat pages, including YouTube live chats embedded on other websites, to display the favorites bar and interact with YouTube’s emote picker. It processes the relevant page elements in your browser to identify emotes you choose to add, validate emotes when the picker is opened, and insert a selected favorite into chat.

The add-on does not send chat messages, browsing history, favorites, or analytics to the developer.

### Emote images

Custom emote images in the favorites bar are loaded directly from YouTube’s and Google’s image servers, the same servers YouTube’s own chat uses. The add-on never loads emote images from any other server. If a saved image address points somewhere else, for example in an imported backup file, that emote is shown as its text shortcut instead.

### Check & Prune

Check & Prune finds custom emotes a channel has removed, as well as duplicate or invalid favorites. It only runs when you start it from the add-on’s settings page. When it runs, the add-on:

- Contacts YouTube to confirm your connection before checking anything
- Loads each saved custom emote image from YouTube’s or Google’s image servers to see whether it still exists

These requests are made directly from your browser, are sent without referrer information, and do not include your favorites or settings. Nothing is removed until you review the results and choose which items to remove.

### Backups

When you choose Export, the add-on creates a JSON backup file containing your settings and favorites. You decide where to save, store, or transfer that file. The add-on does not upload the backup to the developer.

### Services operated by others

Browser sync is provided by your browser provider, not by the developer of this add-on. Emote images are served by YouTube and Google, according to [Google’s Privacy Policy](https://policies.google.com/privacy). GitHub Pages hosts this policy page; GitHub may process visitor information, such as IP addresses, for site operation and security, according to [GitHub’s Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

### Managing your information

You can edit or remove favorites in the add-on, delete a channel-specific list, or use the reset option to clear the add-on’s saved settings. Exported backup files are separate copies; delete them yourself if you no longer want to keep them.

### Contact

For questions about this policy or the add-on, contact: support@socks.email

## Disclaimer & Warranty

### Independent add-on

Favorite Emotes Bar for YouTube Chat is an independent add-on. It is not affiliated with, endorsed by, or sponsored by YouTube, Google LLC, or their affiliates. YouTube is a trademark of Google LLC.

### “As is”

This add-on is provided “as is” and “as available,” without warranties of any kind, to the extent permitted by applicable law.

### Limitation of liability

Use the add-on at your own risk. YouTube may change its website, live chat, or related functionality, which may cause the add-on to stop working or behave unexpectedly. To the extent permitted by applicable law, the developer is not liable for damages or losses resulting from use or inability to use the add-on, including loss of settings or backup files.

Nothing in this disclaimer limits rights or remedies that cannot legally be excluded.
