<h1>Mirra</h1>

[简体中文](README.zh-CN.md) | English

**Control your iPhone directly from Windows.** Mirra is a free iPhone mirroring and control tool with no account required. It does more than show your screen: you can use your computer's mouse and keyboard to operate your iPhone.

https://github.com/user-attachments/assets/ab38bbb8-6147-4619-b7e5-6e7c557f95c2

Free · Closed source · No account · No iPhone app · No jailbreak · Local connection

Windows / macOS · Wi-Fi / USB · iOS 27+

## Download

Go to [GitHub Releases](https://github.com/nodnix/mirra/releases) and choose the package for your computer. The Windows version is a portable ZIP: extract it and run Mirra without an installer.

> **First launch on Windows:** Mirra is free, closed-source software without a code-signing certificate. Windows may show a “Windows protected your PC” SmartScreen prompt. After confirming that you downloaded Mirra from the official Release, select **More info → Run anyway** to launch it.

<a id="getting-started"></a>

## Quick start

**Before you begin:**

- Your iPhone must run iOS 27 or later with Developer Mode enabled. Mirra provides in-app instructions.
- Use Windows 10/11 on an x64 computer, or macOS 14 or later on an Apple Silicon Mac.
- For Wi-Fi, connect the computer and iPhone to the same local network. For USB, use a cable that supports data transfer.
- An internet connection is needed to prepare connection components the first time.

To connect over Wi-Fi: download and open Mirra → choose Wi-Fi → enable Developer Mode → pair the devices → wait for first-time preparation → start controlling your iPhone. For USB, choose “USB” and follow the prompts to connect the cable and trust the computer.

https://github.com/user-attachments/assets/e572b948-ee1e-428f-8eb4-faae2ccc1e82

<a id="faq"></a>

## FAQ

### Why can't I find Developer Mode under Privacy & Security?

Connect your iPhone and computer to the same local network. In Mirra, select “Connect a new iPhone → Wi-Fi → Not enabled / Not sure → Start setup.” Mirra broadcasts on the local network; you should then be able to find the Developer Mode option on your iPhone.

You can also enable Developer Mode with a tool such as Xcode or Aisi Assistant (爱思助手).

### Can I control my iPhone over the internet while I'm away from home?

No. Mirra currently supports Wi-Fi on the same local network and USB. It does not offer control over the public internet.

### Why does the picture keep updating while my iPhone does not respond?

Some iOS permission prompts may not appear in the mirrored picture. Check your physical iPhone and respond to any prompt there before continuing.

### Why can't Mirra find my iPhone?

For Wi-Fi, check that both devices are on the same local network. For USB, check the cable and whether you have trusted the computer on your iPhone.

### Why doesn't my company's Wi-Fi network work?

The network may restrict discovery protocols such as mDNS. Try USB instead.

### What if preparation of the connection components fails?

Check your internet connection and try again. Include the error code shown in Mirra when reporting the problem.

### What should I do if Windows says “Windows protected your PC”?

Mirra is currently unsigned. After confirming that you downloaded it from the official Release, select “More info → Run anyway.”

## Feedback and releases

If you encounter a problem or would like a new feature, tell us what you were trying to do. Your use case helps us understand the request.

**Feedback:** [GitHub Issues](https://github.com/nodnix/mirra/issues).

When reporting a problem, please include your Mirra version, computer operating system, iPhone model and iOS version, connection type, and steps to reproduce it when possible. Do not post passwords, pairing codes, pairing credentials, or unredacted private logs in a public issue.

<a id="community"></a>

You can also join the **Mirra QQ group** (`1126919301`) to discuss problems and feature ideas.

<img src="assets/qq.png" alt="QR code for the Mirra QQ group" width="200">

## Privacy and licenses

Mirroring and control travel directly between your computer and iPhone over your local network or USB. Mirra does not relay the video through its cloud. Preparing connection components, startup analytics, and feedback you choose to submit may use the internet.

[Privacy](PRIVACY.md) · [Terms of use](TERMS.md) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Open-source software rights](OPEN_SOURCE_RIGHTS.md) · [Report a security issue](SECURITY.md)

Mirra itself is not open source. Open-source components distributed with it remain subject to their own licenses; their source code is not the source code of the Mirra product.
