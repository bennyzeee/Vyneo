<p align="center">
  <img src="assets/vyneo-opening.png" alt="Vyneo: a Jellyfin client for Windows and Android" width="520">
</p>

<h1 align="center">Vyneo</h1>

<p align="center">
  <b>A Jellyfin client for Windows and Android that feels like the streaming apps you already love.</b><br>
  A proper video player (libmpv) inside a smooth, calm interface.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-Windows%2010%20%2F%2011-7C5CF0?style=for-the-badge&logo=windows11&logoColor=white" alt="Download for Windows"></a>
  &nbsp;
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-Android%208%2B-B050F0?style=for-the-badge&logo=android&logoColor=white" alt="Download for Android"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Jellyfin-10.9%2B-00A4DC?style=flat-square&logo=jellyfin&logoColor=white" alt="Jellyfin 10.9+">
  <img src="https://img.shields.io/badge/Player-libmpv-6D4DF0?style=flat-square" alt="libmpv">
  <img src="https://img.shields.io/badge/Windows-WinUI%203-0078D4?style=flat-square&logo=windows&logoColor=white" alt="WinUI 3">
  <img src="https://img.shields.io/badge/Android-Jetpack%20Compose-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose">
  <img src="https://img.shields.io/badge/Tracking-none-4c4c4c?style=flat-square" alt="No tracking">
</p>

<p align="center">
  <a href="#download">Download</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#features">Features</a> ·
  <a href="#faq">FAQ</a> ·
  <a href="#support-vyneo">Support</a> ·
  <a href="#privacy">Privacy</a>
</p>

---

## Download

| | | |
| --- | --- | --- |
| 🪟 **Windows 10 / 11** (64-bit) | `Vyneo-Setup-*.exe` | Installs for your user only, no administrator rights |
| 🤖 **Android 8.0 or newer** | `Vyneo-Android-*.apk` | Phones and tablets |
| 📺 **Android TV** | coming soon | A full redesign for the big screen is in the works |

Both files are on the **[Releases](../../releases/latest)** page. You need a Jellyfin server (10.9 or newer is best). Vyneo does not host or provide any media, and is not affiliated with the Jellyfin project.

> **Windows says "Windows protected your PC"?** The installer is not signed yet. Choose **More info → Run anyway**.
>
> **Android:** open the APK and allow installs from your browser or files app when asked.
>
> **Updating:** run the new installer. It finds your installed Vyneo and offers to update it, reinstall or uninstall. Windows can also check by itself under *Settings → About → Check for updates*.

## Screenshots

### On Windows

<p align="center">
  <img src="assets/win-home.jpg" width="100%" alt="Vyneo on Windows: Home with the rotating banner and Continue Watching">
</p>

<p align="center">
  <img src="assets/win-details.jpg" width="49%" alt="A movie page with the cast">
  <img src="assets/win-movies.jpg" width="49%" alt="A library, with watched titles and progress">
</p>

<p align="center">
  <img src="assets/win-rows.jpg" width="49%" alt="Home rows">
  <img src="assets/win-search.jpg" width="49%" alt="Search with filters">
</p>

### On your phone

<p align="center">
  <img src="assets/phone-home.jpg" width="250" alt="Vyneo on Android: Home">
  &nbsp;&nbsp;
  <img src="assets/phone-details.jpg" width="250" alt="A movie page">
  &nbsp;&nbsp;
  <img src="assets/phone-favourites.jpg" width="250" alt="Favourites">
</p>

<sub>Screenshots use a demo library; posters and artwork belong to their respective owners.</sub>

## Features

<table>
<tr>
<td width="50%" valign="top">

### 🎬 A player that plays everything
- Almost any video, audio and subtitle format, including **PGS and styled ASS subtitles**
- The server is asked first, so **Direct Play** is used whenever it can be
- **Smart Fit** removes black bars baked into a video, only when that really makes the picture bigger
- Audio and subtitle picker with the language shown, subtitle timing, speed and streaming quality
- **Seek-bar previews**, **Skip Intro**, **Up Next** with auto-play, Previous / Next episode
- Resumes where you stopped, remembers your tracks per show
- Picture-in-picture, and a mini player on Windows

</td>
<td width="50%" valign="top">

### ✨ Browse in style
- Home with a rotating banner, Continue Watching and Latest rows
- Libraries, **Search** with filters and recently opened titles, **Favourites**
- **Discover** through Jellyseerr: browse what is popular and request what your server does not have, signing in with your Jellyfin account
- Details with cast, episodes, seasons, media info and trailers
- Watch history and stats, several profiles and servers, home and remote addresses
- Windows: right-click a poster to mark it watched or favourite it

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 Made to feel good
- Smooth animations, a violet look, and a soft glow taken from the artwork on screen
- **Windows:** Low Performance Mode, Discord status, Stats for Nerds, and an installer with its own opening animation
- **Android:** a glass navigation bar, swipe for brightness and volume, double-tap to skip, and a battery-saver mode that drops the heavy effects when the phone runs warm

</td>
<td width="50%" valign="top">

### 🛠️ For server owners (Pro)
**Server admin** shows who is watching right now, a readable activity log (who played what, when, and who actually finished it), library tools, and restart or shut down for your server.

</td>
</tr>
</table>

## FAQ

<details>
<summary><b>Does Vyneo come with movies or shows?</b></summary>
<br>
No. Vyneo is only a player for <i>your own</i> Jellyfin server. It does not host, provide or link to any media.
</details>

<details>
<summary><b>Which Jellyfin version do I need?</b></summary>
<br>
10.9 or newer works; Skip Intro needs 10.10 or newer, and seek-bar thumbnails need trickplay turned on in your server.
</details>

<details>
<summary><b>Is it free?</b></summary>
<br>
Yes. Everything for watching, browsing and requesting is free, for everyone, for good. Only the Server admin tools are <b>Pro</b>.
</details>

<details>
<summary><b>Why does Windows warn me when I install it?</b></summary>
<br>
The installer is not code-signed yet, which is a paid certificate. Choose <i>More info → Run anyway</i>. The installer is plain and only installs for your own user.
</details>

<details>
<summary><b>Will it work on my Android TV?</b></summary>
<br>
Not yet. The phone and tablet app is ready; a full redesign for the TV is in the works.
</details>

<details>
<summary><b>Where is the source code?</b></summary>
<br>
The source is private for now. This repository holds the downloads and release notes.
</details>

## Support Vyneo

Vyneo is made by one person, in the evenings. Everything for watching, browsing and requesting is free, for everyone, for good.
If it makes your movie nights nicer, open **Settings → Send Support** inside the app:

- **5 dollars or more:** a ★ Supporter badge, plus colour themes and fonts on Android
- **10 dollars or more:** unlocks **Pro** (Server admin) for good

## Privacy

Your password only goes to your own Jellyfin (and, if you use Discover, your own Jellyseerr) server. Vyneo has no accounts and no tracking.
The only things it fetches from the internet on its own are [`supporters.json`](supporters.json), a small list the app reads to know who has a badge or Pro, and (on Windows) the release list to check for updates.

## About this repository

This repository only holds the downloads and that one file. The app's source code is private. Built with libmpv (LGPL), WinUI 3, Jetpack Compose, Montserrat and Inter (SIL Open Font License).

<sub>Vyneo, a Jellyfin client for Windows and Android (formerly Finity). Jellyfin app for Windows, Jellyfin app for Android, Jellyfin player, libmpv.</sub>
