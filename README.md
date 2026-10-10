# Qevora — Custom QR Code Generator

Qevora is a responsive, browser-based QR code generator for creating, customizing, previewing, and downloading static QR codes without an account.

This repository distributes the original project as a **password-protected 7-Zip archive**. Unencrypted application source is intentionally not published here.

## Features

- Nine QR types: website, text, Wi-Fi, email, phone, SMS, WhatsApp, vCard contact, and geographic location.
- Live generation with validation, color customization, dot and corner styles, and local logo uploads.
- PNG, SVG, and JPEG downloads with high-resolution output options.
- Responsive layouts, sticky navigation, dark mode, keyboard access, and privacy preferences.
- Local browser processing of QR content and logos.
- Pre-rendered informational pages, SEO metadata, sitemap, and robots.txt.
- Reserved space for future advertising, with no live advertising or tracking installed.

## Technologies

React, Vite, Tailwind CSS, JavaScript, HTML5, CSS3, QR Code Styling, and Lucide icons. Tests include Node.js assertions, Playwright browser checks, and independent QR decoding.

## Live website

A public live website URL has not been configured. This repository is an archive distribution, not a hosted application.

## Download

1. Open `Website-Source-Protected.7z` in this repository.
2. Select **Download raw file** to save the actual archive. Alternatively, use **Code → Download ZIP**, then extract the outer GitHub ZIP to find the encrypted `.7z` file.
3. Obtain the password privately from the project owner. The password is not published in this repository.

## Extract with 7-Zip

1. Install [7-Zip from its official website](https://www.7-zip.org/).
2. Right-click `Website-Source-Protected.7z` and select **7-Zip → Extract to “Website-Source-Protected\”**. On Windows 11, you may first need **Show more options**.
3. Enter the password in 7-Zip's password dialog.
4. Open the extracted `Qevora-Source` folder and follow its `README.md` and `PRIVATE-VERCEL-SETUP.md`.

The archive uses the real **7z format, LZMA2 compression, AES-256 encryption, and encrypted filenames**. A correct password is required to list the source filenames and extract the project. Do not rename it to ZIP. Built-in archive tools may not support encrypted 7z archives; use 7-Zip.

## Access and deployment

Downloading the archive does not grant access without the password. Password recipients can view and copy the extracted source, so distribute access only to trusted recipients.

Vercel cannot build directly from this encrypted archive. Deployment requires the extracted source in a separate **private** repository. A deployed website necessarily delivers its public frontend HTML, CSS, JavaScript, and assets to visitors; archive encryption protects this downloadable source package, not those browser-delivered assets.

Source access does not grant redistribution or other rights beyond permission from the project owner. No open-source license is granted by this public README.
