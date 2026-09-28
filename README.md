# rclone-pi

Landing and privacy page for a **personal, single-user** Google OAuth client.

The client exists so [rclone](https://rclone.org/) can read its owner's own Google
Drive from the owner's own Raspberry Pi — mounting one Drive folder as a read-only
audiobook library for a self-hosted server on that machine.

- One user: the account owner, who is also the client's developer.
- Read-only grant (`drive.readonly`).
- No data collection, no analytics, no third-party services.

Pages:

- `index.html` — application home page
- `privacy.html` — privacy policy

Both URLs are referenced from the OAuth consent screen's Branding configuration.
