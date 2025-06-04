# Manus Desktop
Manus (manus.im) is a powerful AI agent you can set up as a native desktop app easily

![image](https://github.com/user-attachments/assets/eb0c47ba-5e98-421d-9b96-0090fb938506)

To get Manus running locally as a desktop app, Open your terminal and run:

```
npm install -g nativefier
```

Once installed, run:

```
nativefier --name "Manus MacOS" https://manus.im
```

Nativefier should have compiled manus.im into a native desktop app which you can find in ~/Manus MacOS-darwin-arm64

Clicking on this should open Manus as a native desktop app!

Yeah it's that simple — built on top of [manus.im](https://manus.im) using [Nativefier](https://github.com/nativefier/nativefier). enjoy your local manus and feel free to pin it to your taskbar.

Note that if you zip and share the .app or .dmg, you will run into apple signing/notarization issues (hence why the files in the releases are broken). If you have a way around this, send me a DM (x.com/0xSigil) and I can update the release for everyone. 

Manus team please ship an official one <3


### Usage:

Recommend to create an email/password account on manus.im, then login to the desktop app. 

Chromium Bugs: 
- Google sign in does not work 
- Account creation OTP verification does not work
