# GitShot privacy & security policy

We built GitShot knowing that (y)our work is precious, and so we made it as secure as possible. If you have any questions or suggestions, please feel free to open an issue!

**TL;DR: We don't have access to the work you do in GitHub/GitShot, nor your personal information.**

In particular:
- Your *GitHub credentials* are securely stored in your iPhone keychain. This is encrypted locally on your device. We never send your access token to anyone outside of GitHub's own API, not even ourselves, so even if our accounts got breached, the attacker would never have a way to access our user's code.
- Your *screenshots* are uploaded anonymously to a paid imgur account where their URL is secret. Screenshots are uploaded from your phone to imgur directly, we never have access to their URLs. The screenshots are then embedded in your Github issue body, directly referencing the imgur URL, so the only people with access to the screenshot are the ones with access to the issue on GitHub. (We wish we could use GitHub's user content CDN, but they don't provide an API for this. We are in touch with them but they don't have an ETA, feel free to ask them too!) 

The only information we collect is statistical usage data, through Fabric's iOS SDK. We currently collect the following events:
- Login with Github (successful/failed)
- Issue opened

This also means we don't have access to your personal details such as email address, GitHub username, etc. (so if you want to hear from us, ping us!)

That's it! We hope you enjoy using GitShot, knowing that your projects are super safe with it :)
