# GeoPicks beta downloads

GeoPicks is a Mac and Windows app for geologists, independents and consultants who map from well logs and seismic. It runs on your own machine, and your project data stays there.

- **Raster-native logs:** pick tops directly on scanned PDF well logs. You don't need to digitize or have LAS files.
- **Correlation:** hang wells on a datum, pick tops across cross sections, mark fault cuts and catch bad picks with QC checks.
- **2D and 3D seismic:** load 2D lines and 3D SEG-Y, tie wells to the seismic with checkshots or synthetics, and pick and auto-track horizons.
- **Seismic attributes:** envelope, phase, frequency and sweetness, plus horizon attribute maps such as RMS amplitude.
- **Maps:** structure and isopach maps from your picks and horizons, fault-aware gridding, hand-drawn contours, and production and lease layers.
- **Volumetrics and output:** closure and spill point, GRV and OOIP/OGIP estimates, plots to scale, ZMap grids, shapefiles, a PowerPoint deck and a PDF prospect pack.

This repository only hosts the beta installers and contains no source code. Learn more and sign up for the beta at **https://getgeopicks.com**.

## Download (always the newest beta)

- **Mac:** [GeoPicks-mac.dmg](https://github.com/reecejk/geopicks-beta/releases/latest/download/GeoPicks-mac.dmg)
- **Windows:** [GeoPicks-windows-setup.exe](https://github.com/reecejk/geopicks-beta/releases/latest/download/GeoPicks-windows-setup.exe)
- **Checksums:** [SHA256SUMS.txt](https://github.com/reecejk/geopicks-beta/releases/latest/download/SHA256SUMS.txt)

All versions and release notes: [Releases](https://github.com/reecejk/geopicks-beta/releases)

## Install on a Mac

1. Open the downloaded `.dmg` and drag **GeoPicks** into **Applications**.
2. The beta isn't signed by Apple yet. The first time you open it, **right-click (or Control-click) GeoPicks in Applications, choose Open**, then click **Open** again.
3. On macOS Sequoia (15) or later you may only see "Move to Trash" and "Done". Click **Done**, then open **System Settings > Privacy & Security**, scroll down and click **Open Anyway** next to the GeoPicks message. Confirm with your password.
4. After that first launch, GeoPicks opens normally.

## Install on Windows

1. Run `GeoPicks-windows-setup.exe`.
2. The beta installer isn't code-signed yet, so Windows SmartScreen may say "Windows protected your PC". Click **More info**, then **Run anyway**.
3. Follow the installer, then start GeoPicks from the Start menu.

## Get your beta key and activate

GeoPicks needs a license key to run. Each beta key is signed for one computer.

1. Sign up for the beta at [getgeopicks.com](https://getgeopicks.com/#beta).
2. Install GeoPicks and open it. The **Activate** page shows **Your Machine ID**, which looks like `GPM-XXXX-XXXX-XXXX`. Click **Copy**, or use the link next to it to email it.
3. Send that Machine ID to geopicks.software@gmail.com, or reply to your beta email with it. If you entered it on the signup form, you don't need to send it again.
4. Your free 3-month beta key arrives by email, usually within 1 business day. It starts with `GP2.`. Paste it on the Activate page and click **Activate**. Activation works offline.

The key works only on the computer whose Machine ID you sent. To use another computer, send that computer's Machine ID.

**3 more months free:** near the end of your beta key, GeoPicks shows a link to the short [feedback form](https://getgeopicks.com/feedback.html). Fill it in and you'll get a key for 3 more months, 6 months in total. A new key replaces the old one on the Activate page. If a key expires, you get 14 days of full use, then GeoPicks becomes read-only. Your projects are never deleted.

## Try the demo

The **Demo Data** project is listed on the home screen and opens on first launch. It's a **synthetic field**: 42 made-up wells with scanned-style raster logs, picked tops, growth-fault cuts, 2D and 3D seismic, checkshots, production and leases, all generated from one earth model. None of it is real data, and it's labeled synthetic in the app.

## Updates

GeoPicks checks this page for a new beta once a day at launch. You can also click **Check for updates** on the home screen or the About page. When a new version is out, click **Update now**. GeoPicks downloads the installer, checks it against `SHA256SUMS.txt` and installs it. Your projects, license key and settings are kept.

## Feedback and support

Bug reports and suggestions are the point of the beta.

- Feedback form: https://getgeopicks.com/feedback.html
- Email: geopicks.software@gmail.com. Say what you were doing, what happened, and your Mac or Windows version, and include a screenshot if you can.

Computer-gridded maps, volumes and depth conversions are a starting point. GeoPicks labels them as automated estimates, so check them against your own geologic interpretation before you make decisions.

J. Kevin Reece, PhD · GeoPicks
