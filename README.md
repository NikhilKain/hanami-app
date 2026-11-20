<div align="center">

<img src="docs/feature-graphic.png" width="100%" alt="Hanami — your next episode, your own pace">

<br>

**A watch list for anime, series and films.**<br>
Material 3 Expressive, written in Kotlin and Jetpack Compose.<br>
Free, with no ads or Hanami account. Your list lives on your phone, with optional Trakt sync.

<br>

<a href="https://github.com/NikhilKain/hanami-app/releases/latest"><img src="https://img.shields.io/github/v/release/NikhilKain/hanami-app?include_prereleases&style=for-the-badge&label=Download%20APK&color=E8B2D0&labelColor=38243F" alt="Download the APK"></a>
<img src="https://img.shields.io/badge/Android-10%2B-E8B2D0?style=for-the-badge&labelColor=38243F&logo=android&logoColor=white" alt="Android 10 and up">
<a href="https://t.me/hanami_tracker"><img src="https://img.shields.io/badge/Telegram-channel-E8B2D0?style=for-the-badge&labelColor=38243F&logo=telegram&logoColor=white" alt="Telegram channel"></a>

<br><br>

<a href="docs/screenshots/01-home.png"><img src="docs/screenshots/01-home.png" width="19%" alt="Home: continue watching"></a>
<a href="docs/screenshots/05-detail.png"><img src="docs/screenshots/05-detail.png" width="19%" alt="A title's page with progress"></a>
<a href="docs/screenshots/02-library.png"><img src="docs/screenshots/02-library.png" width="19%" alt="Library shelves"></a>
<a href="docs/screenshots/06-stats.png"><img src="docs/screenshots/06-stats.png" width="19%" alt="Your numbers"></a>
<a href="docs/screenshots/07-trakt.png"><img src="docs/screenshots/07-trakt.png" width="19%" alt="Trakt sync"></a>

<br>

[Features](#whats-inside) · [Trakt](#trakt-sync) · [Install](#install) · [Privacy](#privacy) · [FAQ](#faq) · [Support](#support)

</div>

<br>

## Why Hanami?

Most trackers want an account before they'll let you tick off a single episode. Hanami
doesn't. Search for something, save it, and press **Watched** when you finish an
episode. Hanami keeps your place, tells you what's next and lets you know when a show
you're caught up on gets a new episode.

It doesn't stream, download or link to video. It's a tracker and nothing else.

## What's inside

<table>
<tr>
<td width="50%" valign="top">

**Keep your place**<br>
One tap marks the next episode watched. Seasons, long-running anime and films are all
counted properly, and every change can be undone.

</td>
<td width="50%" valign="top">

**Know what's next**<br>
Home shows what you're in the middle of. Schedule lists upcoming episodes and releases
for everything you follow.

</td>
</tr>
<tr>
<td valign="top">

**Discover**<br>
Trending, airing now, this season's anime and picks based on what you've saved, all
from TMDB.

</td>
<td valign="top">

**Your numbers**<br>
Hours watched, a daily activity heatmap, streaks, month by month, the days and times
you watch most, and your most-watched titles.

</td>
</tr>
<tr>
<td valign="top">

**Share to Hanami**<br>
Share a link, reel, screenshot or clip from another app. Hanami reads the caption and
any text in the picture on your phone, and can match anime scenes with trace.moe if
you allow it.

</td>
<td valign="top">

**Tracks itself, if you want**<br>
Grant Notification access and choose which video apps to track. Hanami reads playback
information on your phone and can sync the resulting watch history if you connect Trakt.

</td>
</tr>
<tr>
<td valign="top">

**Reminders and alerts**<br>
Pick a day to be reminded about something on your list, and get a note when a show
returns or a film comes out.

</td>
<td valign="top">

**Material 3 Expressive**<br>
Expressive motion and shapes, colours taken from each title's artwork, light and dark
themes, and layouts that work on phones and tablets.

</td>
</tr>
</table>

## Trakt sync

Already tracking on [Trakt](https://trakt.tv)? Open **Settings → Tracking → Trakt → Connect Trakt**,
enter the code Hanami shows at trakt.tv/activate, and approve.

- Your watch history, watchlist and scores come into Hanami.
- From then on, everything you mark watched goes to Trakt within seconds, with the date
  you watched it. Your Planned list and scores stay in step too.
- Episodes are matched by their position in the show, so long anime split into seasons
  differently on TMDB and Trakt (One Piece, for example) still line up.
- When you mark a whole show watched at once, Trakt gets each episode's air date
  instead of today's.

Trakt sync covers watch history, planned titles and ratings. Notes, reminders and
tracking preferences stay outside Trakt sync.

## Install

| Where | |
|---|---|
| **Google Play** | Available to invited closed-test members. |
| **GitHub** | Download the APK from [Releases](https://github.com/NikhilKain/hanami-app/releases). |

Requires Android 10 or newer. The GitHub and Play copies use different signing keys,
so switching requires an uninstall. Sync with Trakt first to bring back your watch
history, planned titles and ratings. Uninstalling removes local notes and reminders.

<details>
<summary>Android says "Restricted setting" when you turn on episode tracking</summary>

<br>

Android blocks Notification access for apps installed from outside an app store until you
allow it. Open Hanami's **App info**, tap **⋮ → Allow restricted settings**, then try
again. Copies from Google Play don't need this step.

</details>

## Privacy

- No account and no ads. An anonymous check-in counts how many phones use Hanami (a scrambled
  device ID, phone model and versions), never your list or searches.
- Your list, progress, notes and reminders are stored on your phone.
- Searches and saved titles are looked up on TMDB. Trakt, trace.moe and crash reports
  are only used if you choose to use them.
- Google's ML Kit (text recognition) sends its own SDK diagnostics, but not your images
  or the text it reads.

Read the full [privacy policy](https://nikhilkain.github.io/hanami-privacy/).

## FAQ

<details>
<summary>Can I watch things in Hanami?</summary>
<br>No. Hanami tracks what you watch elsewhere. It doesn't stream, download or link to video.
</details>

<details>
<summary>Where do titles, posters and episode details come from?</summary>
<br>From <a href="https://www.themoviedb.org">TMDB</a>. If something is wrong there, it's wrong here too, and it fixes itself once TMDB is corrected.
</details>

<details>
<summary>Is the source code available?</summary>
<br>Not at the moment. This repository holds releases, screenshots and documentation.
</details>

<details>
<summary>How do I move my list to a new phone?</summary>
<br>Connect Trakt on both phones, or restore your Android backup on the new one.
</details>

## Support

- News and release notes: [t.me/hanami_tracker](https://t.me/hanami_tracker)
- Questions and help: [t.me/vythera_apps](https://t.me/vythera_apps)
- Email: narzo9990@gmail.com
- In the app: **Settings → Help → Send feedback** to report a bug, request a feature or send a
  message. After a crash, Hanami saves the log to Download/Hanami so you can attach it.

Bugs and ideas are welcome as [issues](https://github.com/NikhilKain/hanami-app/issues).

## Credits

<img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_short-8e7b30f73a4020692ccca9c88bafe5dcb6f8a62a4c6bc55cd9ba82bb2cd95f6c.svg" height="14" alt="TMDB logo">&nbsp; This product uses the TMDB API but is not endorsed or certified by TMDB.

Hanami uses Trakt but is not endorsed or certified by Trakt. Anime scene matching by [trace.moe](https://trace.moe).
Text recognition by Google ML Kit. Type set in Google Sans Flex.

<br>

<div align="center">
<sub>Hanami by Vythera · © 2026 · All rights reserved</sub>
</div>
