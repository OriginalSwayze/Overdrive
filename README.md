# OVERDRIVE

**A neon cyberpunk HUD for the Steam client.** A [Millennium](https://steambrew.app) theme.

![Overdrive library](media/library.gif)

Overdrive rebuilds Steam as a heads-up display. Cut-corner panels float over a living
neon city with a grid floor running toward you. Tabs are slanted slabs, the game list
reads like a data feed, and the Play button glitches when you reach for it.

## Highlights

| | |
|---|---|
| **Living city** | Flickering red, cyan and yellow neon haze over a 3D grid floor that scrolls toward you, plus CRT scanlines and a slow scan beam. |
| **HUD chrome** | Cut-corner panels with edge marks and system tags, a glitching `OVERDRIVE` logo, and a live clock and network readout in the top bar. |
| **Navigator** | Store / Library / Community as slanted tabs; a striped yellow slab slides to the active one. |
| **Data-feed library** | `// COLLECTION` headers in monospace, cyan rails on hover, and the selected game shown dark on yellow. |
| **Covers** | Cut corners, 3D tilt toward the cursor, a scan-line glare and a neon frame. |
| **Game page** | The game logo glitches in when the page opens. The Play button is a striped yellow slab that slice-glitches on hover. Progress bars are segmented neon. |
| **Boot sequence** | An `OVERDRIVE` boot screen when the Steam window opens (it can be turned off). |
| **Everywhere** | Right-click menus, notifications (`INCOMING // TRANSMISSION`), the sign-in reticle, settings, friends and chat, and the Store and Community pages. |

![Game page](media/gamepage.gif)

## Boot sequence

![Boot sequence](media/boot.gif)

## Signals: five palettes plus your own

![Palettes](media/signals.gif)

**Voltage** (yellow / cyan / red), **Redline**, **Netwave**, **Toxic** and **Chrome**.
Pick **Custom** to use your own four colors from the theme's Colors page.

## Options

Open **Millennium → Themes → Overdrive** to change any of these:

- **Look:** Signal palette · City (Live / Static / Blackout) · Grid floor · Scanlines (Normal / Heavy CRT / Off) · Corner cut · Panel opacity · Panel blur
- **Layout:** Floating or Seamless panels · Navigator position · Game list density · What's New shelf · Dock labels · HUD clock
- **Motion:** Glitch (Full / Subtle / Off) · Boot sequence · Motion (Full / Calm / Still) · Cover hover (Tilt / Lift / Off) · Cursor light
- **Extras:** Privacy blur on your account name and wallet

Overdrive honors Windows' *reduce motion* setting, and **Motion → Still** turns off every
animation the theme adds.

## Install

1. Install [Millennium](https://steambrew.app).
2. Install Overdrive from the [theme gallery](https://steambrew.app/themes), or clone this repo into
   `Steam/millennium/themes/Overdrive`.
3. In Steam, open **Millennium → Themes** and select **Overdrive**.

## Notes

- Fonts: Bahnschrift and Cascadia Mono. Both ship with Windows, so the theme loads nothing remote.
- Overdrive is an original cyberpunk-genre design. It is not affiliated with Valve or with any game,
  and it uses no game's name, logo, fonts or artwork.
- Steam updates sometimes rename the client's internal classes. If something looks off after a
  Steam update, please open an issue.

## Changelog

### 1.1.0
- **Friends list:** Steam's gray bars and gradients are gone from the Friends tab, the list, the Group Chats header and the footer. Section bars now get the yellow HUD treatment. Offline friends are dimmed but readable, and the quick-access drop zone is restyled.
- **Community:** Overdrive styling for hub and community-home cards, discussions (unread topics are marked cyan), the activity feed, the Market, Inventory, the Friends page, Badges, Workshop and group pages, page footers, and online/in-game avatar rings.
- **Store:** the new store header and search suggestions, the featured carousel, DLC rows, the queue panel, search filters, the account page, and section headings.
- **Client:** Downloads page sections, the Collections grid, review highlights, the scroll-to-top button, focused rows in Settings, and the Notifications header button.

### 1.0.0
- First release.

## License

[MIT](LICENSE)
