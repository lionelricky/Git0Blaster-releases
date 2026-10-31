# Git0Blaster

A desktop Git client for Windows.

© 2026 RIKmedia · projectGit0Blaster@gmail.com

## Features

- **Commit graph** of every branch, with lanes and branch/tag labels, search, show/hide or solo branches, and a row for uncommitted changes. Stays fast on repos with 10,000+ commits
- **Staging**: stage, unstage and discard whole files, single hunks or single lines; amend; Ctrl+Enter to commit; commit hooks and signing respected
- **Diffs**: side by side or unified, word diff, image diffs (side by side, swipe, onion skin), PDF preview
- **Branches and tags**: create, checkout, rename, delete, merge (squash and `--no-ff`), rebase, interactive rebase, upstream tracking, drag a branch onto another to merge or rebase
- **Commits**: cherry-pick, revert, reset, checkout, and **Undo** for the last action
- **Merge conflicts**: a built-in resolver for merges, rebases, cherry-picks and stash pops, per hunk or by editing the result
- **Stashes**: save (including untracked files or only selected files), view their changes, apply, pop, drop, make a branch from one
- **Remotes**: fetch (and auto-fetch), pull (merge / rebase / fast-forward only), push (force-with-lease, tags), manage remotes, with progress and cancel
- **History page**: compare any two branches, tags or commits; reflog
- **File history** (follows renames), **blame**, and browsing a commit's files
- **GitHub**: sign in, list your repositories and clone them in one click; HTTPS remotes use that sign-in. SSH keys work as well
- Right-click menus everywhere, keyboard shortcuts you can change, and a command palette
- A **Help** page in the app covering every feature

## Installing

You need **[Git for Windows](https://git-scm.com/download/win)** (2.30 or newer) installed. Git0Blaster runs it for every git operation. If Git isn't found, the app says so when it starts; you can also point it at a git.exe in **Settings → Git**.

1. Download `Git0Blaster-Setup-<version>.exe` from the **[latest release](https://github.com/lionelricky/Git0Blaster-releases/releases/latest)** and run it.
2. The installer isn't code-signed yet, so Windows SmartScreen may say *"Windows protected your PC"*. Click **More info → Run anyway**.
3. Accept the license, pick a folder, and start Git0Blaster from the Start menu or the desktop shortcut.

Settings, the recent repositories list and the GitHub sign-in are kept in `%APPDATA%\Git0Blaster`. The GitHub token is encrypted with Windows' own encryption. Uninstall from **Settings → Apps**.

## License

All rights reserved. Free to download and use; see [LICENSE](LICENSE).
