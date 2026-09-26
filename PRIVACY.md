# Mirra Privacy Notice

[简体中文](PRIVACY.zh-CN.md) | English

Effective date: September 26, 2026

Mirra does not require registration or login. This notice explains how Mirra handles data while providing mirroring, control, connection component preparation, and problem reporting.

## Mirroring and control

Your iPhone's screen, audio, and control commands travel between your computer and iPhone over the local network or USB. They do not pass through a Mirra cloud video relay and are not uploaded as part of startup analytics.

Screenshots and recordings are saved in a folder you choose on your computer. Mirra does not upload them automatically.

## Data stored on your computer

Mirra may store the following locally:

- Pairing information needed to connect to your iPhone;
- Preferences such as interface language, window position, volume, and save folders;
- Queued startup events awaiting transmission for up to seven days;
- Feedback drafts, receipts, and limited diagnostic records that you create;
- Screenshots and recordings that you choose to save.

Pairing information and feedback receipts are stored using operating-system secure storage or files with restricted permissions. Removing the app may not remove this local data; that depends on the operating system and how you uninstall it.

## Startup analytics

Each time Mirra starts, it may attempt to send events used to improve the experience. These include:

- A randomly generated installation identifier;
- A random event identifier and startup time;
- The Mirra version;
- Windows or macOS and the processor architecture.

Startup analytics do not contain your name, email address, account, computer name, iPhone name or identifier, an IP-address field, pairing information, screenshots, audio, video, input content, interaction history, or usage duration. Because the random installation identifier can link startup events from the same installation, this data should not be described as fully anonymous.

Queued events are kept locally for no more than seven days. Server-side events are retained for no more than 90 days, and backups for no more than an additional seven days. Startup analytics are used only to understand version and platform distribution and app launches, not for advertising or user profiling.

## Problem reports

Mirra sends a problem report only when you choose to submit it. A report may contain:

- The issue category and description you provide;
- A contact email address, if you choose to provide one;
- The Mirra version, computer operating system and version, and processor architecture;
- Limited diagnostic information you choose to attach.

Limited diagnostics record structured states such as version and connection stage. They do not contain your iPhone screen, audio, input content, clipboard text, pairing credentials, or raw logs. You can review or export the diagnostic content before sending it.

Reports and attachments are retained for no more than 90 days. You can use the locally stored receipt in Mirra's “My Feedback” page to check a report's status or delete it. The corresponding data may remain in backups for up to seven additional days. Deleting the local receipt does not delete the server-side report and prevents this computer from looking up or deleting it later.

## Other network requests

On first connection, Mirra may download verified connection components and contact Apple verification services. These requests do not carry your iPhone screen, audio, or input content. Mirra currently does not automatically check for or download new app versions; new versions are published on [GitHub Releases](https://github.com/nodnix/mirra/releases).

## Data sharing

Mirra does not sell or share personal data with third parties, and does not use it for advertising or user profiling. Apart from the startup analytics and problem reports described above, it does not send user data to other services.

Content you post to GitHub Issues or another public community is made public by you and is also subject to that platform's privacy policy. Do not post passwords, pairing codes, pairing credentials, or logs or screenshots containing private information.

## Contact and updates

For privacy questions, contact the maintainers through [GitHub Issues](https://github.com/nodnix/mirra/issues). Do not include sensitive information in a public issue. If private information is involved, use Mirra's in-app problem reporting feature instead.

We will update this notice and its effective date when the features or data handling practices materially change.
