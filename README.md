# Matrix-Sidecar

A Windows app for a Matrix-Scroller LED panel (Pimoroni Interstate 75 W): it sends Windows notifications,
messages, emoji, gallery images and timers to the panel through your own free Cloudflare Worker.

This repository holds only the download. No source code, no keys.

## Download

[Matrix-Sidecar-0.4.1-win-x64.zip](Matrix-Sidecar-0.4.1-win-x64.zip) (version 0.4.1, about 10 MB; needs Matrix-Scroller firmware 0.4.1 and relay 3.0.1, which the app deploys with **Update the Worker**)

Needs Windows 11 (x64), the .NET 10 Desktop Runtime and the Windows App Runtime 1.8. If one is missing, the app
offers its download when it starts.

## Install

1. Download the zip, right-click it and choose **Extract All**.
2. Open the folder and run **MatrixSidecar.exe**. No admin rights are needed.
3. Follow the app's **Setup guide**: make a Cloudflare API token, then **Deploy the Worker**.

The app isn't code-signed, so Windows SmartScreen may warn the first time: **More info > Run anyway**.

**Never paste a key or token into a chat, an email or a file you share.**
