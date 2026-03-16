# QuickDSi

**Version 0.0.1 (beta).** Feedback welcome.

QuickDSi gets your SD card ready for DSi modding in three steps: check the card, format it if needed, then install everything you need. No tech skills required.

**Community:** [Join our Discord](https://discord.gg/t2C9eqK8FZ) (Quick DSi Modder server).

---

## Get started (on your Mac)

1. **Download** the zip file from the [Releases](https://github.com/bennyfranc0/QuickDSiModder/releases) page.
2. **Unzip** the file. You'll see **QuickDSi.app**.
3. **Double‑click QuickDSi.app** to open it.
4. If your Mac says the app is from an unidentified developer: go to **System Settings → Privacy & Security** and click **Open Anyway** for QuickDSi. Then open the app again.

That's it. You don't need to type anything in Terminal or install extra software. The release also includes **ReadMe.pdf** — the same step-by-step guide in PDF form.

---

## What you need

- A **Mac** with macOS 14 or newer.
- An **SD card** (2 GB to 32 GB) and a way to plug it into your Mac.
- A **Nintendo DSi** (any region).
- **Internet** (so the app can download the files).

---

## Step by step: prepare your SD card

1. **Insert your SD card** into your Mac.
2. **Open QuickDSi.**
3. **Read the legal disclaimer** (first time you open QuickDSi a disclaimer sheet appears and must be accepted). Go through the three onboarding pages, then click **Accept & Get Started**.
4. In the app, **choose your SD card** from the dropdown (or pick "Other…" and choose the card's folder).
5. The app **checks your card**.
   - If it says **"Your SD card is ready"** → click **Next** and skip to step 8.
   - If it says **the card needs to be formatted** → continue to step 6.
6. **Backup (optional but recommended):** Click **Choose backup folder** and pick a folder on your Mac. Then click **Back up now** if you want to save the card's current contents.
7. **Format the card:** Click **Format for DSi**. Enter your Mac password when asked. If the app can't format it, it will show you a short command to run in Terminal — copy it, open Terminal, paste, press Enter, type your password when asked. When it's done, go back to QuickDSi and click **I formatted — refresh**. Then click **Next**.
8. **Deploy:** Read the warning about backing up your NAND, then click **I understand, continue**. Choose options if you want (Memory Pit, box art — see below). Click **Deploy** and wait until it finishes.
9. **Eject the SD card** from your Mac and **put it in your DSi**.

---

## On your DSi

1. Turn on the DSi with the SD card in it.
2. Open the **Camera** app and use the exploit (Memory Pit or the option you chose) to start the custom menu.
3. **Back up your NAND first** — in the menu, run **dumpTool** and save the backup somewhere safe. Do this before installing Unlaunch.
4. **Install Unlaunch last** — run the Unlaunch installer from the menu, follow the prompts, then restart the DSi.
5. After restart you'll see Unlaunch. Go to **Options → No Button → TWiLight Menu++ → Save & Exit** so your DSi boots into the game menu by default.

For the full official guide, see [dsi.cfw.guide](https://dsi.cfw.guide).

---

## Box art (game covers) — optional

If you want cover art for your games on the DSi menu:

- In **Step 3 (Deploy)** in QuickDSi, turn on **Install box art** and click **Use my own box art folder…** to pick a folder of images (PNG files named by game ID). You can get art from [GameTDB](https://www.gametdb.com) and put it in a folder, then select that folder in the app.

Box art is from GameTDB. QuickDSi does not host or claim rights to that content.

---

## If something goes wrong

- **"Empty MBR" or "Bad MBR" on the DSi:** The card wasn't formatted the way the DSi needs. In QuickDSi, go back to Step 2, format the card again (or run the Terminal command the app shows), then run Deploy again.

---

## Disclaimer

QuickDSi is not affiliated with Nintendo or [dsi.cfw.guide](https://dsi.cfw.guide). Modding your DSi may void its warranty and has risks (for example bricking). You are responsible for backing up your data and following the guide. Use at your own risk. The app downloads files from their official sources; we do not modify them.

The QuickDSi app icon is fan art and is not affiliated with or endorsed by Nintendo, Game Freak, or The Pokémon Company.

---

## Donate

**Keep the project running.** If Quick DSi Modder helped you, a donation is a great way to say thanks.

**When sending, please use memo:** **Quick DSi Modder - Donation**

Tap or click an address to copy.

| Asset | Address | Donate link |
|-------|---------|-------------|
| BSV / MNEE | `1PJKRVMN2Rg3fGi8sQERgUmriBAZhUUQEa` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=bitcoin%3A1PJKRVMN2Rg3fGi8sQERgUmriBAZhUUQEa%3Fmessage%3DQuick%2520DSi%2520Modder%2520-%2520Donation) |
| Bitcoin (BTC) | `1Ls2B31cSLKfSKQsSfCyhSsrXnQJkJgyUk` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=bitcoin%3A1Ls2B31cSLKfSKQsSfCyhSsrXnQJkJgyUk%3Fmessage%3DQuick%2520DSi%2520Modder%2520-%2520Donation) |
| Bitcoin Cash (BCH) | `bitcoincash:qrmt44wh7v00hrdz2qzzxzdja3y2glaxvsu27vcl2e` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=bitcoincash%3Aqrmt44wh7v00hrdz2qzzxzdja3y2glaxvsu27vcl2e%3Fmessage%3DQuick%2520DSi%2520Modder%2520-%2520Donation) |
| BCH (Tokens Only) | `bitcoincash:zrmt44wh7v00hrdz2qzzxzdja3y2glaxvsmqdjke42` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=bitcoincash%3Azrmt44wh7v00hrdz2qzzxzdja3y2glaxvsmqdjke42) |
| Litecoin (LTC) | `LNWgV8QuCkYW4tH8gxNHrZ2HXUUKnFQGAD` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=litecoin%3ALNWgV8QuCkYW4tH8gxNHrZ2HXUUKnFQGAD%3Fmessage%3DQuick%2520DSi%2520Modder%2520-%2520Donation) |
| Dogecoin (DOGE) | `DFJWJJqDrcZdBBsxVn67vnu8YoqQw8oQcL` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=dogecoin%3ADFJWJJqDrcZdBBsxVn67vnu8YoqQw8oQcL%3Fmessage%3DQuick%2520DSi%2520Modder%2520-%2520Donation) |
| Ethereum (ETH) | `0x9096313642C991483dA5802190fA7D1D5a324D31` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=ethereum%3A0x9096313642C991483dA5802190fA7D1D5a324D31) |
| Solana (SOL) | `FVoiTWu3uoPRWxae5Bd1EroR9Vfgq7MAj4e5kcu7b2UZ` | [Show QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=FVoiTWu3uoPRWxae5Bd1EroR9Vfgq7MAj4e5kcu7b2UZ) |

**Monero (XMR)** — use this address:

```
47G5hGruEhf6RqFC7FYmdEXwQB2EbFniUiiiJDEMAABB3AWW5UEkMh8Ecmf3Uk1Y4R1DfZ4RPZjCeYmfqFJP8okAHU4eeRX
```

For ETH and Solana, please add memo **Quick DSi Modder - Donation** in your wallet if it supports a memo/message field.

---

## Credits

- [dsi.cfw.guide](https://dsi.cfw.guide) — the guide this app follows.
- TWiLight Menu++, Unlaunch, dumpTool, Memory Pit — the teams behind those projects.
- [YourKalamity](https://github.com/YourKalamity) — [Lazy DSi file downloader](https://github.com/YourKalamity/lazy-dsi-file-downloader-archive); QuickDSi is based on that project's flow.

## License

GPL-3.0 (see LICENSE).

---

## For developers (build from source)

This repo is a fork of [Lazy DSi file downloader](https://github.com/YourKalamity/lazy-dsi-file-downloader-archive); QuickDSi is a native macOS app for [dsi.cfw.guide](https://dsi.cfw.guide). **Topics:** QuickDSi, DSi modding, SD card, dsi.cfw.guide, macos, swift.

**Build and run:**

```bash
cd /path/to/LazyDSiDownloader
swift build
swift run QuickDSi
```

Or open the folder in Xcode and add the `Sources/QuickDSi` files to a new macOS App target, then run.

**Building for distribution:** ReadMe.pdf is generated from **docs/UserGuide.md**. To produce `dist/QuickDSi.app`, `dist/QuickDSi-macOS.zip`, and `dist/ReadMe.pdf`, run `./Scripts/build-to-dist.sh [VERSION]` (requires pandoc for the PDF). For app-only output with no zip or PDF, use `./Scripts/build-release.sh [VERSION]`.

**Publish to GitHub (QuickDSiModder):** Run `./Scripts/build-to-dist.sh [VERSION]`, then `./Scripts/push-to-quickdsimodder.sh` to push QuickDSi-macOS.zip and ReadMe.pdf.

Full step-by-step test walkthrough (app + DSi hardware): [docs/DSI_MODDING_WALKTHROUGH.md](docs/DSI_MODDING_WALKTHROUGH.md).

### Formatting (Step 2) — Terminal script

The SD card must be formatted with **MBR** and **32KB clusters**. If the app can't format the card (e.g. macOS blocks direct disk access), it shows a script to run in Terminal. Replace `diskX` with your SD disk (e.g. `disk4`):

```bash
diskutil unmountDisk /dev/diskX
diskutil partitionDisk /dev/diskX 1 MBRFormat "MS-DOS FAT32" DSI 100%
diskutil unmountDisk /dev/diskX
sudo newfs_msdos -F 32 -c 64 -v DSI /dev/rdiskXs1
diskutil mountDisk /dev/diskX
```

The `-c 64` option gives 32KB clusters (64 × 512 bytes) on 512-byte-sector cards.

### Box art — building a local set from GameTDB

To build a local box art folder for use in the app: install **pngquant** (`brew install pngquant`) and run `./Scripts/update_boxart.sh`. Output goes to `boxart/` at the repo root (gitignored). In Step 3 (Deploy), turn on **Install box art** and choose that folder with **Use my own box art folder…**. The script optimizes images for TWiLight (128×115, ≤ 44 KiB for Cached mode). The repo does not distribute third-party box art.
