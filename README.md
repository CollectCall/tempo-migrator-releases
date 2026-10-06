# Tempo migrator

Copies Tempo data, like worklogs, teams and timesheet approvals, from one Jira site to another.
This repository only has the releases of the app.

## Download

Get the [latest release](https://github.com/CollectCall/tempo-migrator-releases/releases/latest):

- **Mac:** `Tempo-Migrator-mac.dmg`. Open it and drag `Tempo Migrator` to the Applications folder next to it,
  then open it from Applications. The first time macOS can say that it can not check the app: open
  System Settings > Privacy & Security and click Open Anyway.
- **Windows:** `Tempo-Migrator-windows.zip`. Unzip it and double-click `Tempo Migrator.exe`. The first time
  Windows can say that it protected the computer: click More info, then Run anyway.

The app opens in the browser. It updates itself: when there is a new version, the page offers to install it.
The other files of a release are what the app downloads for that.

## Signatures

Each zip has a `.sig` file with its signature. The app only installs updates that are signed with the key
of the releases.
