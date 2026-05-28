<p align="center">
  <a href="https://www.openapk.net"><img src="https://raw.githubusercontent.com/mobilenetworkltd/openapk/main/public/openapk-512.png" height="128" alt="OpenAPK.net"></a>
  <h2 align="center"><a href="https://www.openapk.net">OpenAPK Android</a></h2>
  <p align="center">A native Android wrapper for the best curated list of open source apps. Browse OpenAPK without the browser UI!</p>
</p>

<p align="center">
  <a href="https://github.com/mobilenetworkltd/openapk#popular">Popular</a> &nbsp;&middot;&nbsp; 
  <a href="https://github.com/mobilenetworkltd/openapk#new">New</a> &nbsp;&middot;&nbsp; 
  <a href="https://github.com/mobilenetworkltd/openapk#updated">Updated</a> &nbsp;&middot;&nbsp; 
  <a href="https://github.com/mobilenetworkltd/openapk#featured">Featured</a>
</p>

<p align="center">
  <img src="https://i.imgur.com/waxVImv.png" alt="OpenAPK Banner">
</p>

---

I love [OpenAPK](https://github.com/mobilenetworkltd/openapk), it's easily the best directory for finding FOSS Android apps. But the thing is, unlike F-Droid or other stores, OpenAPK doesn't actually have a native app. You're forced to use the website in a browser, and honestly, I hate that. I don't want to "Add to Home Screen" as a PWA, I just wanted a proper, native-feeling app experience that simply doesn't exist yet.

So I built this. It's a simple, no-nonsense Android wrapper for OpenAPK. It does one thing: gives you the OpenAPK directory as a dedicated app on your phone so you can find open-source apps without the friction of a browser.

---

> ## A Note on "Why"
>
> For everyone that finds this useless—it’s okay. I’m not trying to convince anyone of anything. This is a workflow that is very subjective and personal. Personally, it’s just annoying to me to open OpenAPK as a website in a browser. There’s no logical or mathematical reason other than personal preference.
>
> It’s totally okay to find this weird or useless. But I highly ask you to just try it. It’s free, safe, and easy. You won’t lose anything. The best part is opening the app and seeing that clean experience. Try it just for testing—I highly suggest it, you might actually like it. I’m not saying this is the "best" way to do it; it’s just the way I like it.

---

## Table of Contents
- [A Note on "Why"](#a-note-on-why)
- [Features](#features)
- [How it works](#how-it-works)
- [Installation](#installation)
- [Tech Stack](#tech-stack)
- [Credits](#credits)

---

## Features
- Ultra Lightweight: The OpenAPK APK is only 864 KiB. 
- Native Feel: No browser UI, no address bars—just the OpenAPK store.
- Clean Experience: It behaves exactly like an app should, keeping your OpenAPK browsing focused.

---

## How it works
The app is a dedicated wrapper for the official OpenAPK website. 
1. Browse: Open the app and browse the OpenAPK directory exactly as you would on the web.
2. Download: When you find an app you want to install, clicking the download link will trigger your default browser.
3. Confirm: You'll see the standard system popup ("Download file?"). Click download to start, and you're good to go.

---

## Installation
1. Go to the [Releases](https://github.com/YOUR_USERNAME/openapk-android/releases) section.
2. Download the `openapk.apk` wrapper.
3. Install it on your Android device (ensure "Install from Unknown Sources" is enabled).

---

## Tech Stack
This project was made possible by the awesome [website-to-apk](https://github.com/Jipok/website-to-apk) tool. It’s a really cool project that let me turn the OpenAPK site into this lightweight WebView wrapper without any bloat.

## Credits
- [MobileNetworkLtd/openapk](https://github.com/mobilenetworkltd/openapk) for the amazing directory.
- [Jipok/website-to-apk](https://github.com/Jipok/website-to-apk) for the great tool that made this happen.
