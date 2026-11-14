# OldMan Stream Companion

### Your stream has enough moving parts already.

**Free. Local. Your computer. Your stream. Your tools. Your data.**

OldMan Stream Companion (OMSC) brings Twitch chat, music, viewer requests,
custom alerts, on-stream widgets and community tools together in one Windows
application. Give your viewers more ways to take part, customise how music and
alerts appear on stream, and manage the tools behind it from one dashboard.

There is no monthly OMSC subscription. Choose the modules you need, connect your
accounts, and keep your settings, media and stream history on your own computer.

[Official website & live previews](https://oldmanstreamcompanion.com/) ·
[Downloads](https://github.com/DeeJai1/OldMan-Stream-Companion-Public/releases) ·
[Chat command reference](https://oldmanstreamcompanion.com/commands/) ·
[Discord community](https://discord.gg/SG4fTGx7cP)

> **Public download: Coming Soon.** The Windows installer will appear on this
> repository's Releases page when the public release is ready. Visit the
> [official website](https://oldmanstreamcompanion.com/) for launch information.

---

## What can OMSC do for your stream?

### Spotify, song requests & Now Playing widgets

Turn your music into part of the show and give your community a say in what
plays next.

- Control Spotify playback from OMSC, including play/pause, previous/next track
  and volume.
- Accept song requests through supported Twitch chat commands or Channel Point
  rewards, and manage the request queue from the app.
- Set request rules and cooldowns, and block tracks or artists you do not want
  on your stream.
- Show the current track and artwork in OBS with customisable Now Playing
  widgets, including Equaliser Tower, Vinyl Player, Spectrum Ring and Classic
  layouts.

### A playlist built by your community

Give your viewers a lasting place in your stream's music collection.

- Let viewers contribute Spotify tracks to your community playlist.
- Keep contributor credits and review who added each song.
- Explore playlist insights such as most-played tracks and songs waiting for
  their first play.
- Search and manage playlist entries, remove unwanted tracks, and maintain
  song and artist blacklists.

### Native Twitch chat, commands & timed messages

Handle everyday chat interactions directly through OMSC.

- Connect your broadcaster account and, optionally, a separate Twitch bot account.
- Configure command names, prefixes, permissions and enabled commands to suit
  your channel.
- Let viewers use supported commands for music, playlist information and other
  OMSC features, while keeping moderation actions restricted appropriately.
- Schedule timed messages with interval and chat-activity controls for reminders,
  links and announcements.
- Create Auto-Replies with custom command names, cooldowns, audience permissions
  and a choice of saved response lines, using an authorised separate bot account.

OMSC's native Twitch chat, commands and supported event handling run directly
through the app. Streamer.bot can remain part of your setup for other automations.
See the [command reference](https://oldmanstreamcompanion.com/commands/) for
examples; actual triggers depend on your channel configuration.

### Custom sound & video alerts

Build viewer-triggered moments using your own sounds, clips and visual style.

- Create audio-only or video alerts using media stored on your computer.
- Browse supported Creati and Pexels media searches and save selected clips
  locally for your alerts.
- Link supported alerts to Twitch Channel Point rewards.
- Adjust playback, volume, appearance and positioning, with optional green-screen
  removal for video.
- Apply cooldowns and per-stream limits to keep redemptions manageable.
- Preview and test alerts before showing them in OBS.

### Twitch event celebrations

Give follows, subscriptions, resubscriptions, gifted subscriptions and Bits their
own presentation.

- Enable the supported events you want OMSC to handle.
- Configure event-specific banners, images, audio and video.
- Customise text, colours, sizing, animation and timing to match your stream.
- Test event visuals through the app before using them live.

Available events and reward actions depend on the permissions granted to your
Twitch account and the features enabled in OMSC.

### Shoutouts & raid welcomes

Welcome a visiting community and give other creators a moment on your stream.

- Build shoutout and raid welcome banners with creator profiles, artwork and
  custom text.
- Include raid viewer counts and optional local audio or video in your welcome.
- Choose from multiple designs and adjust colours, fonts, borders, sizing and
  placement.
- Preview your design and send test actions to OBS before going live.

### Desktop Chat & local alert overlays

Keep important stream activity in sight while you play.

- Place a movable Twitch chat overlay over your desktop or game.
- Use click-through behaviour to keep chat visible without taking clicks away
  from the game.
- Use the local Game Overlay to display supported alert visuals on your own
  screen using your existing designs, without an OBS connection for that overlay.
- Keep OBS in charge of stream audio: the local Game Overlay is silent.

Desktop overlays support windowed and borderless fullscreen games. Exclusive
fullscreen is unsupported. Auto-Replies and Game Overlay currently carry a
**Requires Testing** label in the app; test them with your setup before live use.

### Stream credits that recognise your community

Give the people who supported your stream a proper send-off.

- Record supported stream events and supporter activity locally for your credits.
- Review the current credits session and control the presentation in OBS.
- Choose from Perspective Crawl, Spotlight, Retro Arcade, Terminal and Classic
  Roll layouts.
- Customise and preview your credits to suit your stream's look.

### Stream analytics & local history

Look back at your streams and understand how your community participates.

- Review locally saved stream sessions and stream history.
- See participation information such as unique chatters and returning participants.
- Explore recorded engagement and supporter activity over time.
- Keep that history on your computer. Watch Streaks indicate loyalty, rather than
  measured viewer watch-time.

### A dashboard that fits your workflow

Keep the controls you use most within reach.

- Choose which dashboard tiles are visible, change their order and resize them.
- Check connection status, music playback and the song request queue in one place.
- Configure and test modules before you go live.
- Use OMSC's supplied Browser Source URLs to bring music widgets, alerts, banners
  and credits into your OBS scenes.

### Community discovery, backups & support tools

- **Streamer Directory:** choose whether to list your Twitch channel, discover
  other participating streamers and see who is live. Listing is opt-in.
- **Backup & Restore:** export supported settings and data, keep a recovery copy,
  or restore them when moving to another computer. Portable backups omit
  machine-bound Twitch and Spotify authentication tokens, so reconnect accounts
  after moving computers.
- **Help & diagnostics:** use the in-app FAQ, feedback tools and diagnostic
  information when you need help with your setup.

## Getting started

Once the public installer is available:

1. Download `OldManStreamCompanion-Setup-X.Y.Z.exe` from the
   [official Releases page](https://github.com/DeeJai1/OldMan-Stream-Companion-Public/releases)
   and follow the Windows setup prompts.
2. Open OMSC and use **Connections** to authorise the Twitch accounts and other
   services you want to use.
3. Enable your chosen modules and customise their settings, media and designs.
4. Add the supplied widget URLs to OBS as Browser Sources. Configure the OBS
   WebSocket connection when using OMSC's OBS connection features.
5. Use the previews and test controls to check your setup before streaming.

### What you need

- A Windows 10 or Windows 11 computer running the Windows x64 build.
- An internet connection for Twitch, Spotify and other online integrations.
- A Twitch account and the relevant permissions for the Twitch features you enable.
- OBS Studio for displaying OMSC widgets and alerts on your broadcast.
- For Spotify: your own Spotify Developer Client ID and account authorisation.
  Spotify Premium is required for playback controls and Development Mode apps.
- For the local Game Overlay: Microsoft Edge WebView2 Runtime. Follow the app's
  setup prompt if it is missing.

OMSC itself is free. Third-party accounts, subscriptions and service restrictions
still apply. Keep the OMSC application running while using its live stream tools.

## Downloads & updates

This is the official public distribution repository for OldMan Stream Companion.
Published Windows releases will include:

| File | Purpose |
| --- | --- |
| `OldManStreamCompanion-Setup-X.Y.Z.exe` | Windows installer for setting up OMSC. |
| `OldManStreamCompanion-win-x64-vX.Y.Z.zip` | Application package used by the updater. |
| `OldManStreamCompanion-win-x64-vX.Y.Z.zip.sha256` | SHA-256 checksum used to verify the update package. |

Existing installations can check for public updates inside OMSC. Keep a backup
of important settings and media before major changes.

## Get help & share ideas

Visit the [official website](https://oldmanstreamcompanion.com/) for feature
previews and FAQs, or join the
[OMSC Discord community](https://discord.gg/SG4fTGx7cP) for support, feedback and
ideas from other streamers.

When reporting a problem, include your OMSC version, what you were trying to do,
what happened and any steps that reproduce it. Keep account tokens, passwords
and private connection settings out of public reports.

## Licence

OldMan Stream Companion is proprietary software provided free of charge for
personal and commercial streaming use. See [LICENSE.txt](LICENSE.txt) for the
full software licence, including redistribution and modification restrictions.

This repository contains public distribution material. The application source
is maintained separately.
