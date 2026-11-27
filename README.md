# WOOPLI

**A small companion for Windows that is always within reach.** Notes, translation, screenshots and screen
recording, photo and video viewers, dictation and an AI assistant — in a launcher at the top of your screen.

Free (freeware), public beta. Made by Bogdan Vitkov.

> **Download:** see [Releases](../../releases) → `WOOPLI_<version>_x64-setup.exe`. The SHA-256 of every file is in
> the release notes.

---

## What it does

- **Notes** — rich text, pictures, tables, checklists, page view with A4 pages, timeline and Gantt, deadlines,
  colours, export to PDF and Word. Links to files and folders (also on network computers you trust).
- **Translate** — the selected text, a whole note or a screenshot (F14, Shift+F14); local translation with
  TranslateGemma, no internet needed.
- **Screenshots and video** — choose an area (F15), draw arrows, frames and text, copy the text from the shot;
  record the screen with the microphone and system sound (Ctrl+F15), subtitles with Whisper.
- **Photo and video viewers** — strips of the whole folder, picks, compare, rename in batches (F2), cut out an
  object with a transparent background, copy or move files.
- **Dictation** — speak into any note or text field; Whisper runs on your computer.
- **Ask WOOPLI** — ask about pictures, PDFs and files and get a note back (with your own OpenAI key).
- **E-mail and messengers** — send a note (or the note as a PDF) via Outlook, Thunderbird, Gmail, Outlook.com,
  Telegram, WhatsApp or the Windows share window.
- **Weather, clock, calendar** — with Google Calendar sync if you connect your account.

> All hotkeys can be changed in **Settings → Hotkeys**.

## What you need

- Windows 10 or 11, 64-bit.
- About 100 MB for WOOPLI itself.
- **For dictation and local translation:** an NVIDIA graphics card and about 4 GB of disk space. WOOPLI downloads
  these components after installation (Settings → Components). Without NVIDIA everything else works and nothing
  is downloaded.
- Optional: your own OpenAI API key (voice assistant, Ask WOOPLI), your own Google OAuth client (Calendar, Gmail).

## Installing

1. Download `WOOPLI_<version>_x64-setup.exe` from [Releases](../../releases).
2. Windows SmartScreen may say "Windows protected your PC" — the beta is not code-signed yet. Click
   **More info → Run anyway**.
3. Follow the setup. On the last page keep **"Download speech and translation components now"** ticked to get
   dictation and local translation (about 4 GB, NVIDIA only).
4. Updating: run the new setup and choose **Update** — your notes and settings stay.

## Where your data goes

- **On your computer:** notes, settings, screenshots and recordings. Local translation (TranslateGemma), local
  dictation and subtitles (Whisper) run on your computer.
- **OpenAI** (only with your own key): the voice assistant (F6), live translation of system audio (F7), Ask WOOPLI,
  web search and image tools send what they need to OpenAI. Charges go to your OpenAI account.
- **Google** (only if you connect your account): Calendar sync and Gmail drafts. Results of these may be passed to
  the voice assistant; disconnect the integration to keep them out.
- **Other services:** weather from Open-Meteo (your location or city), optional location by IP via GeoJS or
  IPinfo, downloads of the components from Hugging Face and GitHub.
- **Keys:** your OpenAI key, the Google sign-in and the database keys are kept in Windows Credential Manager.
- WOOPLI has no analytics and no server of its own.

## Licence

WOOPLI is freeware: free to use, also at work. You may pass on the unchanged official package. See
[LICENSE.txt](LICENSE.txt) (Deutsch: [LICENSE.de.txt](LICENSE.de.txt)) and
[THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt) for the components it uses.

The source code is not public.

## Feedback

This is a beta. Bugs and ideas: [Issues](../../issues).

© 2026 Bogdan Vitkov
