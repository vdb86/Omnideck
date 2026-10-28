<div align="center">

<img src="Omnideck.png" alt="Omnideck app icon" width="120" height="120" />

# Omnideck

### Your whole phone, one swipe away

**A private floating launcher: apps, contacts, widgets & actions, one swipe away.**

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.omnideck.app">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="80"/>
  </a>
</p>

</div>

---

Omnideck is a floating launcher that lives quietly on the edge of your screen. Swipe in from the side, or tap a floating button, and the **Deck** appears right where you are - no jumping back to the home screen, no digging through app drawers. Tap what you need, and it tucks itself away again.

Beside the Deck there are **Panels**: an A-Z app index and a contacts index, each with its own trigger.

It is built to be fast, tidy, and completely yours.

---

<!-- whats-new:start -->
## 🆕 What's new in 3.4

- More floating buttons (Pro): add up to four more buttons, each with its own look, position, gestures, Action wheel and settings. A new button starts with Button 1's look, next to it.
- Show app names (Pro): names under the icons in the Deck, on one or two lines and in the size you choose, per Deck. Folders can now be named too (Edit on a folder in edit mode).
- Add action never lets you pick more than fits on the page. When it is full, add a row or a column right there and keep adding (Pro).
- Vibrate when a swipe runs (Pro): a new switch for edge swipes, per edge pair.
- Edge swipe with only one edge on: its gestures and Action wheel are now that edge's own - adding apps to the right wheel no longer puts them on the left one too.
- The album cover on the floating button now follows track changes again, also when the button was hidden or the phone was just unlocked.
- Making a page's grid bigger (Add action, the page manager or the default rows / columns) no longer rearranges its icons, folders or widgets - you just get the new empty row or column.
- Several Pro features are now free, including Backup & restore, home-screen icons and Deck position.

[All release notes](RELEASE-NOTES.md)
<!-- whats-new:end -->

---

## 💬 Feedback, bug reports & feature requests

This repository is the home for **reporting issues and requesting features** for Omnideck.

- 🐞 **Found a bug?** [Report a bug](../../issues/new?template=bug_report.yml) and tell us what happened, what you expected, and your device / Android version.
- 💡 **Have an idea?** [Request a feature](../../issues/new?template=feature_request.yml) - I read every suggestion.
- 👍 **Want something that's already been suggested?** Browse [bug reports](../../issues?q=is%3Aissue+label%3Abug) and [feature requests](../../issues?q=is%3Aissue+label%3Aenhancement) and add a 👍 or a comment so I know it matters to you.

Please search the [open issues](../../issues) first to avoid duplicates.

---

## ✨ The Deck

- **Launch anything** - apps, app shortcuts, activities, inner links (an app's own screens and deep links), custom intents, Android settings screens, files, contacts, websites, saved texts, HTTP requests and web searches, all in one panel.
- **Add action, eleven tabs** - Apps, System, Activities, Intents, Inner links, Shortcuts, Files, Websites, Contacts, Text and HTTP. A **Test** button tries an activity or intent before you add it, and screens other apps can't open are marked. Pick several at once - when the page is full, add a row or a column right there and keep going.
- **System actions at a glance** - Back, Home, Recents, Previous app, Notifications, Quick settings, Split screen, Lock screen, Screenshot, Power menu, Assistant, Web search, Torch, volume and mute, media controls (play / pause, previous, next, stop), rotation and Auto-rotate, Screen timeout, Adaptive brightness, and more.
- **Live widgets** - drop your favourite widgets straight into the Deck, then move and resize them on the grid, with zoom control for widgets that don't fit.
- **Up to five Decks** - each with its own pages. Decks 2-5 follow Deck 1's settings until you change one for that Deck (a small reset icon brings it back), and every gesture, wheel slot, home-screen icon and link chooses which Deck it opens.
- **Stay organised** - named folders, multiple pages, a page manager, and a grid size you choose (up to 20 x 20, per page if you like). Making a grid bigger never moves what is already on it.
- **App names** - show names under the icons, on one or two lines and in the size you choose, per Deck.
- **Scroll your way** - flip pages left/right or up/down, or switch to one continuous strip that can loop endlessly.
- **Edit in place** - in edit mode, tap an item to edit it, hold and drag to move it; icons and widgets make room for each other as you drag.
- **Pin it** - keep the Deck on screen and drag it wherever you want it; a "Show / hide Deck" action closes it again, and **Lock position** stops it from being moved by accident.
- **Where it opens** - left, right or centre, at a height you set or right at your finger.
- **Stays out of the way** - close after an action, auto-close after a delay, and move up or click through when the keyboard opens.

---

## 🌐 HTTP requests & Wake-on-LAN

- **Save web requests** (GET, POST, PUT, PATCH, DELETE) with headers, a JSON, text or form body, Basic or Bearer authentication and a timeout - all on one page.
- **Wake-on-LAN** - wake a computer on your network with a magic packet.
- **Import from cURL** - paste a cURL command (also Chrome's "Copy as cURL") and the request fills itself in.
- **Test before saving**, then run it from the Deck, a gesture or the Action wheel.
- **Show the result your way** - a toast, a notification, a dialog, or a full-screen window with the response details, a JSON table, and Copy / Share / Save / Run again.
- **Variables** - write `{{name}}` in a URL, header or body. A variable can be a fixed value, ask you for a text, number, password, date, time, colour or a choice when the request runs, or switch between values on each run. Answers can be JSON-encoded, multi-line, and remembered for next time.
- **Site icons** - websites and requests can fetch the site's own icon.

---

## 🔍 Web search

- **A search box, one tap away** - a Web search action opens a small search card with the keyboard already up, from the Deck, a gesture, the Action wheel or Bottom notifications.
- **Recent searches and live suggestions** - your recent searches show first; as you type, the search engine's own suggestions take over, letter by letter. Recent searches stay on your phone only and can be cleared.
- **11 search engines** - Google, DuckDuckGo, Bing, Brave Search, Ecosia, Qwant and Yahoo, plus Naver, Yandex, Seznam and Baidu. Choose the engine for each action, with a default in Settings > General, and switch to another one for a single search right from its icon in the search box.
- **Your browser** - results open in the default browser or in the browser you pick for that action.
- **Web addresses too** - type example.com and open the site directly instead of searching for it.
- **Search suggestions can be turned off** - then nothing is sent while you type.

---

## 📚 Library

Settings > General > Library lets you edit, duplicate or delete your saved **texts**, **HTTP requests** and **websites** without going through Add action, and shows where each one is in use before you delete it. It opens directly from `omnideck://open/library` (also `/texts`, `/http`, `/websites`).

---

## 📝 Saved texts

Keep texts you type often and paste them into the field you're typing in, from the Deck, a gesture or the Action wheel.

---

## 🗂️ Panels

Two extra surfaces, each with its own trigger, gesture binding and launcher shortcut:

- **App index** - an A-Z rail of every installed app. Slide down the rail and tap the app; long-press for App info, Add to Deck or Uninstall. Hide the apps you never want to see there.
- **Contacts** - your contacts on the same rail, opening on your favourites. Tap someone to get their numbers, emails and address, each with its own call, message, copy or map action - plus the actions WhatsApp, Viber, Telegram and others add themselves. Sort by given or family name, pick a default number, and choose which app actions appear. A whole contact can sit on the Deck for one-tap access.

---

## 🎨 Make it yours

- **75 built-in themes**, **Material You** colours from your wallpaper, or mix your own palette.
- **Dozens of animations** - open/close, folders, taps, 40+ page transitions and 36 show / hide animations for the floating button, each with a live preview and its own speed (0.5x to 2x).
- **Now playing on the button** - while music or video plays, the floating button can show the album art or an animation: Record, Tape, CD, Equalizer, Pulse, Notes, Wave or Ticker.
- **Custom icons** - built-in Material icons, your own icon packs (or one default pack for every app), contact photos, gallery images, or 50+ animated icons for the floating button.
- **Every dimension** - size, shape, position, opacity, corner radius, borders, padding, labels and the toolbar.
- **Light, dark or automatic** for the app's own screens, independently of the overlay theme.

---

## 👆 Open it your way

Settings > Triggers has a page each for the **Button**, **Edge swipe** and **Icons**.

- **Edge-swipe strips** on either side, with a visual hint you can show or hide and a touch area you drag into place on screen - shared by both sides or set separately for each.
- **Up to five edge pairs** - add more left / right pairs of strips, each with its own touch areas, gestures, Action wheel, hint and settings.
- **Directional gestures** - a tap, and short and long swipes in five directions per strip (and eight around the floating button), each bound to any action. Set the angles visually, and how long to hold for a long swipe. Give each strip its own set, or let both share one with **Mirror** (with only one edge on, it always has its own). A short vibration when a swipe runs, if you like.
- **Up to five floating buttons** - each with its own look, position, gestures, Action wheel and rules.
- **A movable floating button** - snap it to an edge (half hidden, above the navigation bar), fling it, choose a different shape when snapped, and let it rotate with the screen or stay put.
- **The Action wheel** - swipe from the floating button or an edge (or tap a strip), slide onto one of the actions around your finger and lift to run it. It opens at your finger or at a fixed spot, with its own opacity. Pick the actions, icons and names in its own editor; each edge strip can have its own wheel.
- **Swipe-through launch** - keep your finger down after the Deck opens, slide onto an item and lift to open it. On or off for the button and for each edge pair.
- **Automatic behaviour, per trigger** - for the button and for each edge pair: in the apps you pick, hide it or let taps go through (and snap / unsnap the button); hide it or let touches through in fullscreen apps; hide it in landscape.
- **Home-screen icons for every Deck** - a left and a right icon per Deck, each opening its Deck or showing / hiding it.
- **Everywhere else** - launcher long-press shortcuts (left and right, for the Deck and each panel), `omnideck://` links, and intents for Tasker or MacroDroid.
- **Works with Bottom notifications** - if you own it, a gesture or wheel slot can open its notification shade, and its own gestures can run Omnideck actions, opening any Deck included.

---

## 🛠️ And also

- **Backup & restore** - your whole setup in one file you control; a file from another app or a newer Omnideck is refused before anything changes.
- **What's new** and an **update checker** inside the app.
- **Debug page** - Settings > About & contact > Debug shows the Pro purchase checks, memory details and a media log in one copyable report, for when you need support.
- **Second-finger protection** - a second finger touching the strip or the button never sets it off.

---

## 📸 Screenshots

<div align="center">

<img src="Screenshots/Popup%20-%20apps%20and%20widgets.jpg" alt="The Deck with apps and widgets" width="30%" />
<img src="Screenshots/Add%20widget.jpg" alt="Add widget" width="30%" />
<img src="Screenshots/Page%20manager.jpg" alt="Page manager" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20apps.jpg" alt="Add action - apps" width="30%" />
<img src="Screenshots/Add%20action%20-%20activities.jpg" alt="Add action - activities" width="30%" />
<img src="Screenshots/Add%20action%20-%20shortcuts.jpg" alt="Add action - app shortcuts" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20intents.jpg" alt="Add action - intents" width="30%" />
<img src="Screenshots/Add%20action%20-%20inner%20links.jpg" alt="Add action - inner links" width="30%" />
<img src="Screenshots/Add%20action%20-%20system.jpg" alt="Add action - system" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20http.jpg" alt="Add action - HTTP requests and Wake-on-LAN" width="30%" />
<img src="Screenshots/Add%20action%20-%20text.jpg" alt="Add action - saved texts" width="30%" />
<img src="Screenshots/Add%20action%20-%20websites.jpg" alt="Add action - websites" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20files.jpg" alt="Add action - files" width="30%" />
<img src="Screenshots/Add%20action%20-%20contact.jpg" alt="Add action - contacts" width="30%" />

<br/><br/>

**Full settings tours (long captures):**
[General](Screenshots/Settings%20-%20general.jpg) ·
[Triggers](Screenshots/Settings%20-%20triggers.jpg) ·
[Panels: Deck](Screenshots/Settings%20-%20panels-%20deck.jpg) ·
[Panels: App index](Screenshots/Settings%20-%20panel%20-%20app%20index.jpg) ·
[Panels: Contacts](Screenshots/Settings%20-%20panel%20-%20contacts.jpg)

</div>

---

## 🔒 Private by design

Omnideck respects your privacy from the ground up:

- **No account, no sign-up, no login. Ever.**
- **No ads. No trackers. No hidden analytics** building a profile of you.
- **Your layout stays on your device** - there is no cloud sync and no automatic cloud backup.
- **Backups belong to you** - export and import your setup as a simple file that only you control.
- The app asks only for what a launcher genuinely needs, and every request is explained in plain language.

---

## 🔑 Permissions, explained honestly

- **Display over other apps** - this is what lets the panel float above whatever you are using.
- **See your installed apps** - so Omnideck can show them for you to launch. That list never leaves your phone.
- **Notifications (optional, recommended)** - lets Android show the small, quiet notification that keeps Omnideck running in the background. You can minimise it in your notification settings.
- **Battery optimisation exemption (optional, recommended)** - stops Android from freezing or closing Omnideck in the background, so the edge strips and the floating button keep working.
- **Contacts (optional)** - only for the Contacts panel and contact shortcuts. Skip it and everything else still works.
- **Modify system settings (optional)** - only for the screen-rotation, Auto-rotate, Screen timeout and Adaptive brightness actions.
- **Internet** - only for the HTTP requests and Wake-on-LAN packets you set up yourself, for fetching a website's icon when you ask for it, and for web search: the search engine's suggestions while you type (each letter goes to the engine you chose - turn suggestions off in Settings and nothing is sent) and each engine's icon, fetched once. Omnideck sends nothing about you anywhere.
- **Usage access (optional)** - only to see which app is in front, so triggers can behave differently in the apps you pick (hide, click through, snap or unsnap). Omnideck never reads your usage history.
- **Accessibility service (optional, OFF by default)** - Omnideck uses Android's Accessibility Service for three things, and only when you choose to use them:
  1. **System navigation shortcuts from the panel** - Back, Home, Recents, Notifications, Quick Settings, Lock screen, Screenshot, and Split screen. Android only exposes these actions through the Accessibility Service (`performGlobalAction`), so the panel relies on it to trigger them.
  2. **Keyboard avoidance** - detecting when the on-screen keyboard opens so the panel can slide out of its way (a Pro feature).
  3. **Pasting saved texts** - an action you set up pastes a text you saved in Omnideck into the text field you are typing in. Omnideck only asks which field has focus and pastes into it; it never reads the field or anything else on screen.

  Omnideck does **NOT** read, record, log, collect, or transmit the contents of your screen or anything you type. No accessibility data is stored or leaves your device. The service is optional and disabled by default; you can turn it off at any time in **Android Settings → Accessibility** or from Omnideck's Permissions screen, and every other feature keeps working without it.

---

## 💎 Free, with an optional one-time upgrade

The free version is genuinely useful all on its own: a full launcher panel, every action type (HTTP requests, Wake-on-LAN, saved texts and web search included), the Library, folders, custom icons, contact menus, themes, Material You, both ways to open it, backup and restore, home-screen icons, and where the Deck opens.

**Omnideck Pro** is a single one-time purchase - no subscriptions, ever. It unlocks the extra polish and customization:

- Up to five Decks, five edge-swipe pairs and five floating buttons
- Bigger grids and extra pages
- Deck appearance (app names included) and behaviour
- Page transitions, animations and haptic feedback
- Vertical and continuous scrolling
- The App index and Contacts panels
- Directional gestures and the Action wheel
- Swipe-through launch
- Floating-button styling, animations and keyboard avoidance
- Per-app trigger rules and fullscreen / landscape behaviour

Buy it once and it is yours to keep.

---

## 🌍 Languages

Omnideck is available in **50 languages** and follows your phone's language automatically:

Arabic, Bengali, Bulgarian, Catalan, Chinese (Simplified), Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, French, German, Greek, Gujarati, Hebrew, Hindi, Hungarian, Icelandic, Indonesian, Italian, Japanese, Kannada, Korean, Latvian, Lithuanian, Malayalam, Marathi, Norwegian, Persian, Polish, Portuguese (Brazil and Portugal), Punjabi, Romanian, Russian, Serbian (Cyrillic and Latin), Slovak, Slovenian, Spanish, Swahili, Swedish, Tamil, Telugu, Thai, Turkish, Ukrainian, Urdu, Vietnamese and Zulu.

If something reads wrong in your language, please [report it](../../issues/new?template=bug_report.yml).

---

## 📌 A few things to know

- Available in **50 languages** (see above).
- Works on **Android 10 and newer**.
- Some phones aggressively close background apps. If the edge strips or the floating button ever stop responding, the in-app tips help keep Omnideck running.

---

<div align="center">

Omnideck is for anyone who wants their phone to feel faster and calmer: everything you reach for most, always a swipe away - and nothing looking over your shoulder.

</div>