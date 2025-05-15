# Fix PowerPoint Font Preview (No More "Download Font" Issues!)

![PowerPoint font preview issue](assets/preview.png)

Are you tired of seeing **"Click to download"** or **missing previews** in PowerPoint fonts?

This repository solves that by letting you **instantly preview all fonts** in PowerPoint without manually clicking each one.

## ✅ What This Fixes

- PowerPoint not showing font previews
- Fonts appearing as "Download font"
- Manually clicking fonts just to preview them

## 💡 How It Works

PowerPoint stores cloud fonts in a hidden local folder. This repo contains **preview cache files** that trick PowerPoint into thinking all fonts are already downloaded.

## 📁 How To Use It

1. Download the contents of the [`Fonts`](./Fonts) folder in this repo.
2. Paste them into this path on your computer:
   C:\Users\YOUR_USERNAME\AppData\Local\Microsoft\FontCache\4\CloudFonts
   (Replace `YOUR_USERNAME` with your actual Windows username.)
3. Restart PowerPoint – all font previews should now be visible!

## 🛠️ Notes

- No fonts are being installed – only preview cache data is used.
- Tested on PowerPoint for Microsoft 365 (Windows 11).

## 📢 Why This Exists

PowerPoint doesn't cache cloud font previews until you click each font one by one. This fix helps you preview **all fonts instantly**, saving time and frustration.

---

## 🔗 Keywords (for search engines)

`PowerPoint font preview fix`, `PowerPoint fonts not showing`, `download font PowerPoint`, `PowerPoint CloudFonts cache`, `font thumbnails PowerPoint not working`
