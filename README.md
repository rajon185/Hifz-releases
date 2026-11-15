# Hifz — Quran memorisation for Android & Android Auto

Listen and memorise the Quran **ayah by ayah**, on your phone or in the car.
Recitation by **Sheikh Mahmoud Khalil Al-Husary (Mujawwad)**.

**[⬇ Download the latest version](https://github.com/rajon185/Hifz-releases/releases/latest)**

---

## What it does

- **All 114 surahs, every ayah.** Pick a surah to play it from the start, or pick any ayah to
  start there.
- **Play modes** (one button on the phone, notification and car screen):
  - **Play surah once:** plays the surah ayah by ayah, then stops.
  - **Repeat ayah:** loops the current ayah until you move on.
  - **Repeat surah:** plays the surah, then starts it again.
  - **Continue to next surah:** keeps going surah after surah.
- **Pause between ayahs:** a short gap (1.5 s by default, adjustable 0–10 s) after every ayah, to
  repeat it to yourself.
- **Arabic text on screen:** the ayah being recited appears as the album art in Android Auto
  (including split screen next to Maps) and in the phone notification.
- **Short surahs first:** an optional list order (Al-Fatihah, then An-Nas, Al-Falaq … Al-Baqarah)
  for learning the surahs used in daily prayer.
- **Works offline:** anything you've listened to is saved. Use **Download surah** to save a whole
  surah before a journey.
- **Duas (Hisn al-Muslim):** all chapters with Arabic, transliteration, English and audio.
- **Revision:** bookmark surahs, ayahs and duas and play them from the *Revision* tab with one tap.
- **Remembers where you were:** reopen the app or start the car and carry on from the same ayah.
- **Car controls:** steering-wheel and controller next/previous move one ayah at a time, and the
  *queue* button in Android Auto lists every ayah of the surah so you can jump to any of them.

## Install

Needs **Android 8.0 or newer**.

1. On your phone, open the
   **[latest release](https://github.com/rajon185/Hifz-releases/releases/latest)**.
2. Under **Assets**, tap **`hifz-v….apk`** to download it.
3. Open the downloaded file. If Android asks, allow your browser (or Files app) to
   **install unknown apps**, then go back and tap **Install**.
4. Open **Hifz** and allow notifications when asked. The playback controls live in the
   notification.

> Android may warn that the app is from an unknown developer. Hifz isn't on the Play Store, so
> this is expected. Tap **More details → Install anyway**.

## Updates

Hifz **updates itself**. When a new version is published here, the app offers **Update** when you
open it. Tap it, then confirm Android's install screen. Your downloads, bookmarks and settings are
kept.

- The first time, Android asks you to allow Hifz to **install apps**. Turn it on and go back.
- You can check by hand in **Settings → App → Check for updates**. The installed version is shown
  there too.

## Use it in Android Auto

Android Auto only shows apps from the Play Store unless you switch on **Unknown sources**. You only
need to do this once:

1. On the phone, open **Settings** and search for **Android Auto** (or go to *Connected devices →
   Connection preferences → Android Auto*).
2. Scroll to the bottom and **tap "Version" about 10 times** until it asks to *Allow development
   settings*. Tap **OK**.
3. Tap the **⋮ menu** (top right) → **Developer settings**.
4. Tick **Unknown sources**.
5. Back on the Android Auto page, open **Customise launcher** and make sure **Hifz** is ticked.
6. Reconnect your phone to the car (unplug it, or switch wireless Android Auto off and on).

Hifz now appears among the car's media apps.

**In the car:**
- **Browse** (list icon): choose a surah, or open it and choose an ayah. Duas and Revision are
  there too.
- **⏮ / ⏭** and the steering-wheel buttons go to the previous or next ayah.
- The **play-mode** button cycles Once → Repeat ayah → Repeat surah → Continue.
- The **queue** button lists every ayah of the current surah. Tap one to jump to it.
- Pause length, surah order and colours are set on the phone (⚙ in the app).

## Troubleshooting

- **"App not installed" / "package conflicts with an existing package":** you have a copy of Hifz
  signed differently (for example a test build). Uninstall it, then install from here. Uninstalling
  removes downloaded audio.
- **Hifz doesn't appear in the car:** check *Unknown sources* and *Customise launcher* (steps 4–5
  above). Then force-stop Android Auto (*Settings → Apps → Android Auto → Force stop*) and reconnect.
- **No sound or ayah won't load:** the first play of each ayah needs internet. Download the surah
  beforehand to listen offline.
- **No update offered:** open **Settings → App → Check for updates**, or download the newest APK
  from the [Releases page](https://github.com/rajon185/Hifz-releases/releases) and install it over
  the top. Nothing is lost.

## About this repository

This repository only hosts the signed release builds. Each release has a version tag (`v1.2.3`)
and the APK attached. Every APK is signed with the same key, so each one installs as an update
to the previous one.

## Credits

- Recitation: Sheikh Mahmoud Khalil Al-Husary (Mujawwad), audio from
  [EveryAyah.com](https://everyayah.com).
- Uthmani Quran text from [The Noble Qur'an Encyclopedia](https://quranenc.com) via
  [quran-json](https://github.com/risan/quran-json) (CC BY 4.0).
- Duas from [Hisn al-Muslim](https://www.hisnmuslim.com/).
- [Amiri Quran](https://github.com/aliftype/amiri) font, SIL Open Font License 1.1.
