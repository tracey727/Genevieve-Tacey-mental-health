# GENEVIEVE LISTENS™ Life Companion v3 — Transferable Pilot

A static GitHub/Vercel-ready PWA using the archived Genevieve health colours and Tree & Roots emblem.

## New in v3

- Password-protected phone-to-phone transfer file
- AES-256-GCM browser encryption
- PBKDF2-SHA-256 key derivation with 250,000 iterations
- iPhone/Android share sheet support when available
- Download fallback for browsers that cannot share files
- Restores check-ins, personal baseline history, tasks, story, supports and settings
- No server upload: the user chooses AirDrop, Files, Messages, email or cloud drive

## Deploy

Upload the contents of this folder to the root of the existing GitHub repository connected to Vercel. Keep Framework Preset as Other with no build command. The existing Vercel domain should remain unchanged.

## Transfer to a new phone

1. Old phone: Me → create password → Create secure phone transfer.
2. Save/send the `.genevieve` file.
3. New phone: open the same live Vercel app and add it to Home Screen.
4. Me → choose secure transfer file → enter password → Restore my Life Companion.
5. Confirm check-ins and reminders are present before deleting the old copy.

## Pilot boundary

This is a private self-use pilot. It is not a clinical record system, emergency monitor, diagnosis tool or replacement for emergency services. No clinician is automatically notified.
