# Android Studio Downloader

Automatically downloads the latest Android Studio for Linux and creates a GitHub Release when Google publishes a new version.

## Features

- Automatically checks for new Android Studio versions
- Runs daily using GitHub Actions
- Creates a new Release only when the version changes
- Downloads the Linux `.tar.gz` archive
- Calculates SHA-256 checksum

## Download

Go to the [Releases](../../releases) page and download the latest version.

## Automation

The workflow runs automatically every day.

You can also run it manually from:

`Actions → Android Studio Release → Run workflow`
