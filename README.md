# ManageSpace — downloads

Downloadable builds of **ManageSpace**, a disk cleaner and folder-size visualiser for
macOS, Windows and Linux. Built by [Akshay Kotish & Co.](https://akshaykotish.com)

**[Download from akshaykotish.com →](https://akshaykotish.com/#managespace-downloads)**
or take any file straight from the [latest release](../../releases/latest).

## What it does

- **One screen** — disk capacity, everything reclaimable, and a size map of any folder, side by side.
- **Reclaimable space** — app caches and logs, Trash, Xcode derived data and device support,
  simulator caches, Homebrew, CocoaPods, iOS backups; `%TEMP%`, INetCache, crash dumps, thumbnail
  cache, Recycle Bin, Windows Update cache, Prefetch; `~/.cache`, thumbnails, `/tmp`, apt/dnf/pacman
  caches, the systemd journal — plus npm, Yarn, pnpm, pip, Gradle, Maven, Cargo, Go, Android and the
  Chrome / Edge / Firefox / Safari caches on every platform.
- **Folder sizes** — every subfolder measured and ranked largest first, with drill-down, the largest
  files, and everything untouched for six months.

## Safety

Deletions go to the Trash or Recycle Bin by default and are restorable; permanent removal is a
separate, deliberate toggle. Volume roots, the home folder, Documents, Desktop, Downloads, `~/.ssh`,
`/System` and `C:\Windows` are refused outright. Locations that nest — `~/Library/Caches` holds the
Homebrew, pip and Chrome caches — never double-count, so the figures add up.

## Installing

| | |
| --- | --- |
| **macOS** | 11 Big Sur or later, Apple silicon and Intel. Signed with an Apple Developer ID but not yet notarised, so the first launch needs a right-click → **Open**. |
| **Windows** | 10 or later. The installer is unsigned — SmartScreen asks once; choose **More info → Run anyway**. The portable build needs no installation. |
| **Linux** | Any modern 64-bit distribution. `chmod +x` the AppImage, or `sudo apt install ./managespace_1.0.0_amd64.deb`. |

No account, no telemetry, works offline.
