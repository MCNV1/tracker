# NVIDIA Tracker

Static single-file PWA for capturing supplier audits, bring-up rejects and field findings. Photos, severity, status, corrective actions — exports to NVIDIA-branded PPTX + Excel.

**Live:** https://mcnv1.github.io/tracker/

## What it is
A pure-client web app. Everything (audits, photos, settings) lives in your browser's `localStorage` — nothing is sent to a server.

## Install on phone
Open the live URL in mobile Safari/Chrome → Share → **Add to Home Screen**. After that it launches fullscreen like a native app, works offline, and shows up alongside your other apps.

## Source of truth
This public mirror is auto-published from the internal NVIDIA portal at gitlab-master. Don't push fixes here — they'll be overwritten on the next sync.
