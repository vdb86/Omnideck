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

## 💬 Feedback, bug reports & feature requests

This repository is the home for **reporting issues and requesting features** for Omnideck.

- 🐞 **Found a bug?** [Report a bug](../../issues/new?template=bug_report.yml) and tell us what happened, what you expected, and your device / Android version.
- 💡 **Have an idea?** [Request a feature](../../issues/new?template=feature_request.yml) - I read every suggestion.
- 👍 **Want something that's already been suggested?** Browse [bug reports](../../issues?q=is%3Aissue+label%3Abug) and [feature requests](../../issues?q=is%3Aissue+label%3Aenhancement) and add a 👍 or a comment so I know it matters to you.

Please search the [open issues](../../issues) first to avoid duplicates.

---

## ✨ The Deck

- **Launch anything** - apps, app shortcuts, activities, custom intents, files, contacts and websites, all in one panel.
- **System actions at a glance** - flip on the flashlight, rotate the screen, take a screenshot and more without leaving what you are doing.
- **Live widgets** - drop your favourite widgets straight into the Deck, then move and resize them on the grid.
- **Stay organized** - folders, multiple pages, and a grid size you choose (per page, if you like).
- **Scroll your way** - flip pages left/right or up/down, or switch to one continuous strip that can loop endlessly.
- **Pin it** - keep the Deck on screen and drag it wherever you want it.

---

## 🗂️ Panels

Two extra surfaces, each with its own trigger, gesture binding and launcher shortcut:

- **App index** - an A-Z rail of every installed app. Slide down the rail and tap the app; long-press for App info, Add to Deck or Uninstall.
- **Contacts** - your contacts on the same rail, opening on your favourites. Tap someone to get their numbers, emails and address, each with its own call, message, copy or map action - plus the actions WhatsApp, Viber, Telegram and others add themselves. A whole contact can sit on the Deck for one-tap access, and you can choose which app actions appear.

---

## 🎨 Make it yours

- **75 built-in themes**, or mix your own palette.
- **Dozens of animations** - open/close, folders, taps and page transitions, each with a live preview.
- **Custom icons** - built-in Material icons, your own icon packs (or one pack for every app at once), contact photos, gallery images, or animated icons for the floating button.
- **Every dimension** - size, position, opacity, corner radius, borders and padding.
- **Light, dark or automatic** for the app's own screens, independently of the overlay theme.

---

## 👆 Open it your way

- **Edge-swipe strips** on either side, with direction-aware gestures: short and long swipes in five directions per side, each bound to whatever you want.
- **A movable floating button** with its own gesture set and optional animated icons.
- **Everywhere else** - launcher long-press shortcuts (left and right, for the Deck and each panel), home-screen icons, `omnideck://` links, and intents for Tasker or MacroDroid.

---

## 📸 Screenshots

<div align="center">

<img src="Screenshots/Popup%20-%20apps%20and%20widgets.jpg" alt="The Deck with apps and widgets" width="30%" />
<img src="Screenshots/Add%20widget.jpg" alt="Add widget" width="30%" />
<img src="Screenshots/Page%20manager.jpg" alt="Page manager" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20apps.jpg" alt="Add action - apps" width="30%" />
<img src="Screenshots/Add%20action%20-%20activities.jpg" alt="Add action - activities" width="30%" />
<img src="Screenshots/Add%20action%20-%20intents.jpg" alt="Add action - intents" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20inner%20links.jpg" alt="Add action - inner links" width="30%" />
<img src="Screenshots/Add%20action%20-%20files.jpg" alt="Add action - files" width="30%" />
<img src="Screenshots/Add%20action%20-%20system.jpg" alt="Add action - system" width="30%" />

<br/>

<img src="Screenshots/Add%20action%20-%20websites.jpg" alt="Add action - websites" width="30%" />
<img src="Screenshots/Add%20action%20-%20contact.jpg" alt="Add action - contacts" width="30%" />

<br/><br/>

**Full settings tours (long captures):**
[General](Screenshots/Settings%20-%20general.jpg) ·
[Triggers](Screenshots/Settings%20-%20triggers.jpg) ·
[Deck](Screenshots/Settings%20-%20popup.jpg)

<sub>Some captures predate the Deck / Panels rename and the newer panels.</sub>

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
- **Modify system settings (optional)** - only for the screen-rotation actions on the Deck.
- **Usage access (optional)** - only to see which app is in front, so triggers can behave differently in the apps you pick (hide, click through, snap or unsnap). Omnideck never reads your usage history.
- **Accessibility service (optional, OFF by default)** - Omnideck uses Android's Accessibility Service for two things, and only when you choose to turn them on:
  1. **System navigation shortcuts from the panel** - Back, Home, Recents, Notifications, Quick Settings, Lock screen, Screenshot, and Split screen. Android only exposes these actions through the Accessibility Service (`performGlobalAction`), so the panel relies on it to trigger them.
  2. **Keyboard avoidance** - detecting when the on-screen keyboard opens so the panel can slide out of its way (a Pro feature).

  Omnideck does **NOT** read, record, log, collect, or transmit the contents of your screen or anything you type. No accessibility data is stored or leaves your device. The service is optional and disabled by default; you can turn it off at any time in **Android Settings → Accessibility** or from Omnideck's Permissions screen, and every other feature keeps working without it.

---

## 💎 Free, with an optional one-time upgrade

The free version is genuinely useful all on its own: a full launcher panel, every action type, folders, custom icons, contact menus, and both ways to open it.

**Omnideck Pro** is a single one-time purchase - no subscriptions, ever. It unlocks the extra polish and customization:

- Bigger grids and extra pages
- Deck appearance, position, and behaviour
- Page transitions, animations and haptic feedback
- Vertical and continuous scrolling
- The App index and Contacts panels
- Floating-button styling and keyboard avoidance
- Backup and restore

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
