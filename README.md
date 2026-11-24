# Mastodon Digital Archive (`@habilozdemircom`)

Permanent, SHA-256 verified digital archive of public Mastodon posts, replies, account metadata, and attached media files.

- **Source Account:** https://mastodon.social/@habilozdemircom
- **Total Archived Posts & Replies:** 210
- **Archived Media Files:** 7
- **Privacy Filter:** Direct/private messages excluded (0 skipped)

## Contents
- `mastodon-public-posts.json` — Structured JSON archive of all 210 public posts and replies.
- `mastodon-posts-readable.txt` — Clean, human-readable chronological plain-text transcript.
- `media/` — All 7 attached images, videos, and documents renamed with SHA-256 digests.
- `MANIFEST.sha256` — Cryptographic SHA-256 checksums for every file in the archive.

## Verification
```bash
shasum -a 256 -c MANIFEST.sha256
```
