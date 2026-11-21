# Coop picker

The Google Drive picker page for the Coop Chrome extension. Google's Picker can't run inside a Chrome extension, so Coop opens this page in a popup window and receives the chosen folder or document through Chrome's extension messaging.

The page holds no keys or data. Coop passes a short-lived Drive token, the Picker API key, the Cloud project number, its extension ID and a one-time code after the `#` in the address, which browsers never send to the server.

The source lives in the Coop extension repository at `picker/index.html`; copy changes here to publish them.
