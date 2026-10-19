# Ask for macOS

Signed downloads and the update feed for Ask, the native Hermes reply bubble. The development repository is private.

[Download the latest release](https://github.com/playboyxbt/ask-releases/releases/latest)

## Upgrade an existing Mac

1. Download and unzip the latest `Ask-…-macOS.zip`.
2. Quit Ask and replace `~/Applications/Ask.app` with the extracted app. In Finder, Home → Applications is the intended folder.
3. Open Ask. Your existing Telegram helper, account login, and local settings remain on that Mac.
4. Use Ask → Check for Updates for later releases. Automatic checks and optional automatic installation are in Settings → Updates.

Each Mac needs this one-time upgrade to acquire the updater. Apple silicon and Intel are supported on macOS 15 or later.

## Personalize the bubble

Open the gear in the reply bubble or Ask → Settings (Command–comma). Choose System, Light, or Dark, adjust opacity and dismissal duration, and record up to two shortcuts. Move the bubble by its empty header and resize it with an edge or the bottom-right grip. Position and size are remembered.

Hovering pauses the countdown; leaving starts it again. Sending hides the bubble until Hermes replies. Timed dismissal keeps unsent drafts available through Last reply.

## Distribution status

These builds are Developer ID signed and use verified Sparkle archive and feed signatures. Apple notarization is not configured yet. This release is for the owner's existing Ask installations; a complete new-customer installer, account onboarding, and paid licensing are separate work.

No Telegram credentials, account sessions, or signing private keys are included in the downloads.
