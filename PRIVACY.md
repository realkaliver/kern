# Privacy Policy

**Application:** Kern (`com.kaliver.kern_reader`)

**Platform:** Android

**Effective date:** <!-- set on publication --> *November 1, 2026*

**Contact:** *kernreader@gmail.com*

---

## Summary

Kern is a reading application that runs on your device. Your library, reading
positions, highlights and notes are stored there.

**There is no Kern account and no Kern server.** The developer operates no
service that receives, stores or processes your data, and never will. Nothing
you read, import, highlight or annotate is sent to the developer.

Kern contains **no analytics, telemetry, advertising or crash-reporting
software**. Your reading is not profiled or sold. Optional reading statistics
are kept for your own use, as described below.

## What Kern stores on your device

| Data | Where it is kept |
|---|---|
| Your library: books, covers, metadata | Local database and file storage on the device |
| Reading positions and history | Local database |
| Highlights, notes, bookmarks | Local database |
| Settings, themes, preferences | Local storage |
| Credentials for services you connect | The Android platform's encrypted secure storage |

This data stays on the device unless you explicitly ask Kern to back it up or
synchronise it, in which case it is written to **storage you own and have
chosen**, never to the developer.

## Reading statistics

Reading Statistics lets Kern keep a history of your reading for features you can
use. It is on by default and can be switched off in Settings under Startup &
Utilities.

| What Kern keeps or estimates | What it gives you |
|---|---|
| Estimated reading speed from your sittings | Personal estimates of time left and what counts as a quick read, including Finish Tonight and Time Left. With statistics off, Kern uses the pace you set in Reading Pace or a default of 230 words per minute. |
| Time read, per sitting and per book | Reading Window, the time line beneath your shelves, Most Read by time and the “most time” figures in library views. |
| When each sitting began and ended, and where it stopped | Recently Read, the reading journal and the read-aloud sitting log; you can return to where a sitting ended. |
| The days you read | Days Read. |
| Each date you finished a book | This Year, reading history and how many times you have read a book. |

With Reading Statistics off, Kern stops recording new sittings and hides Most
Read, This Year, Days Read, Reading Window and Recently Read, along with the
reading journal and other history-based displays. Your saved reading position,
bookmarks and notes still work.

The most recent finish date is retained to support a book’s finished state.

To remove already stored data, switch Reading Statitistics off and tap **Clear
data**. Your finished books, reading positions, bookmarks and notes remain.
Backups you made are separate and remain under your control.

Reading sittings and time read stay on your device and in backups you choose to
make. Finish dates are also included in device sync if you enable it, using
storage you choose.

None of these statistics is sent to the developer or anyone else. They exist in
the app solely to provide a benefit to the user.

## What Kern does not collect

Kern does not collect, transmit or store:

- Your name, email address, phone number or any account identifier for the
  developer's purposes
- Your location
- Your contacts, photos, messages or calendar
- A record of what you read, when, or for how long for the developer
- Advertising identifiers
- Device fingerprints or usage analytics

## When Kern uses the network

Kern connects to the network only where a feature requires it, and only to the
service that feature implies.

| Purpose | Destination | When |
|---|---|---|
| Reading books from cloud storage | The provider you connected | When you connect an account or open a book stored there |
| Backup and multi-device sync | The storage you chose | When you back up, or when your devices reconcile reading position |
| Book metadata and cover art | Open Library | When enriching a book's details |
| Public-domain books | Project Gutenberg | Only if you browse or download from it |
| Speech voices, dictionary packs | Hugging Face, GitHub | When you choose to download an optional asset |
| Exporting highlights and notes | The integration you linked | When an export runs |

Every one of these follows from an action you took. Kern makes no background
connection for the developer's benefit.

## Cloud storage access

Kern connects to cloud storage so you can read books you already have stored,
instead of copying every file onto the device by hand.

Supported: Google Drive, Dropbox, OneDrive, WebDAV, SFTP, SMB, and Calibre
Content Server.

**What Kern does with that access:**

- Reads book files from the folders you select, and the metadata needed to list
  them
- Writes a backup archive to a location you choose, when you ask for a backup
- Writes a small synchronisation record so your own devices can agree on your
  reading position

**What Kern does not do:**

- It does not browse, index or scan storage outside the folders you select
- It does not delete or modify your existing files
- It does not transmit your file contents, file listings or credentials to the
  developer or to any third party
- It does not use storage access for advertising, profiling or analytics

Access tokens are stored in the platform's encrypted secure storage on the
device. You can disconnect a service inside Kern at any time, and revoke Kern's
access separately from the provider's own account settings.

## Third-party integrations

If you choose to link them, Kern can export your highlights and notes to
**Readwise, Notion, Obsidian, Anki, Hardcover** or **BookWyrm**.

Each is off until you enable it, and authorised individually. Only the content
you created (highlights, notes, and the book details they belong to) is sent,
and only to the service you linked. Once data reaches one of these services it
is governed by that service's own privacy policy.

## Permissions, and why each exists

Some of the permissions below are declared by the open-source libraries Kern is
built on rather than by Kern itself. They are listed anyway, because they appear
on the application's permission list and you are entitled to know what they are
for.

| Permission | Why |
|---|---|
| `INTERNET` | Connecting to cloud storage, integrations and asset downloads |
| `ACCESS_NETWORK_STATE` | Detecting whether you are online, so Kern can defer network work and honour offline mode |
| `READ_EXTERNAL_STORAGE` | Opening book files you select from the device. Limited to Android 12 and below (`maxSdkVersion="32"`); on Android 13 and above Kern does not request it |
| `POST_NOTIFICATIONS` | Playback controls, and progress for imports and downloads |
| `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Continuing audiobook playback when the screen is off or you leave the app |
| `WAKE_LOCK` | Preventing the device sleeping mid-playback or mid-narration |
| `USE_BIOMETRIC`, `USE_FINGERPRINT` | Declared by the encrypted-credential library, which can bind stored credentials to the device's hardware-backed keystore |
| `DOWNLOAD_WITHOUT_NOTIFICATION` | Fetching optional voice and dictionary assets without adding a system download notification |

Kern does not request access to your camera, microphone, location, contacts,
calendar, call logs or messages.

## Security

Credentials for services you connect are stored in the Android platform's
encrypted secure storage, which is backed by the device keystore.

Connections to cloud providers and integrations use the encrypted transport
those services require.

Because Kern holds no data on a server, there is no central store of user
information that could be breached.

## Retention and deletion

Kern retains data on your device for as long as the application is installed.

- **Individual items** (books, highlights, notes) can be deleted inside the
  application at any time.
- **Connected services** can be disconnected inside Kern, which removes the
  stored credentials from the device.
- **Everything** is removed when you uninstall the application.
- **Backups and sync records** you created live in your own cloud storage, under
  your control, and you delete them the way you delete any other file there.

The developer holds no copy to delete.

## Children

Kern is a general-purpose reading application. It is not directed at children
under 13, and it does not knowingly collect information from them. As it
collects no personal information from anyone, it holds none belonging to a
child.

## Changes to this policy

If this policy changes, the revised version will be published here with an
updated effective date. Material changes affecting how data is handled will be
noted in the application's release notes.

## Contact

Questions about this policy, or about how Kern handles data:

*kernreader@gmail.com*

Dev's note: I've attempted to avoid the usual weasel words through which some
proprieters circumvent a user's expectation of privacy. If any ambiguity remains,
drop me a line and I will address your concerns. 

You can also raise an issue on the project's issue tracker.
