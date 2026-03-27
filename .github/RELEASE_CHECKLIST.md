# Release Checklist

Use this checklist before publishing a new Naggler release.

## Pre-release

- [ ] All known release-blocking bugs are fixed
- [ ] CHANGELOG.md is updated with new entries under the version heading
- [ ] Version number bumped in app config / build files
- [ ] README.md download links updated to new version
- [ ] QUICKSTART.md reviewed — still accurate with any UI changes

## Build

- [ ] macOS DMG built and tested on Intel Mac
- [ ] macOS DMG built and tested on Apple Silicon Mac
- [ ] Windows zip built and tested on Windows 10+
- [ ] Linux tar.gz built and tested on Ubuntu 20.04+
- [ ] App launches cleanly on first run (no stale config)
- [ ] SQLite database migrates correctly from previous version

## Test

- [ ] Add/reorder/delete priorities
- [ ] Start session, respond to check-ins, end session
- [ ] Pie chart and gap analysis update correctly
- [ ] Day and week views render properly
- [ ] Export CSV, JSON, and HTML — verify output
- [ ] Edge tab appears and responds to clicks
- [ ] Snooze and done task flows work
- [ ] Auto-promote suggestion triggers correctly
- [ ] Focus Score calculates and displays

## Publish

- [ ] Create GitHub release with tag `vX.Y.Z`
- [ ] Upload all platform binaries to the release
- [ ] Write release notes summarizing changes
- [ ] Update Homebrew tap formula (bump version and SHA)
- [ ] Verify `brew install --cask naggler` installs new version
- [ ] Announce release (email list, socials, etc.)

## Post-release

- [ ] Verify download links in README work
- [ ] Smoke test the published DMG/zip/tar.gz from GitHub
- [ ] Close resolved issues and milestone
