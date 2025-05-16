# Cypherpop Protocol

**Cypherpop** is a cultural operating system disguised as a genre.

It is a remixable protocol for encoded music, programmable meaning, and decentralized artistry.  
This repository contains the living documentation, templates, and submission logic for building Cypherpop-compliant track capsules.

---

## What’s in This Repo

| File / Folder          | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `MANIFESTO.md`         | The ideological spine of the protocol—Cypherpop’s declaration of intent |
| `whitepaper.md`        | Deep dive into the philosophy, cultural roots, and genre mechanics      |
| `cyphernary.md`        | Living glossary of terms, logic, memes, and metaphors                   |
| `CHANGELOG.md`         | Version history of the protocol and infrastructure                      |
| `LICENSE`              | MIT license — remix-friendly and permissionless                         |
| `tracks/`              | All verified Cypherpop tracks with full metadata and decoded insight     |
| `starter-kits/`        | Templates for building your own track folders                           |
| `README.md` (this)     | Start here. This is the entrypoint for contributing and understanding   |

---

## What Is a Cypherpop Track?

Each track is a fully self-contained folder that includes:

tracks/
└── your-track-name/
├── README.md # Short summary and notes about the track
├── lyrics.txt # Raw lyrics (plaintext)
├── decoded-lyrics.md # Technical/metaphorical breakdown
└── track.json # Structured metadata: title, bpm, version, etc.


You can optionally add:
- `cover.png` — visual art
- `stems/` — isolated audio tracks

---

## Get Started with a Track

1. **Download the Starter Kit**  
   [track-template.zip](starter-kits/track-template.zip)

2. **Unzip and rename the folder**  
   Example: `tracks/automate-my-soldiers/`

3. **Fill in your data:**
   - `track.json` with metadata
   - `lyrics.txt` with raw lyrics
   - `decoded-lyrics.md` with your deconstruction

4. **Host your `.mp3` somewhere decentralized ideally**  
   (Supabase, IPFS, Arweave, or your own server) and link it in `audio_url`.

5. **Submit your folder via pull request or integrate it into your own fork.**

---

## track.json Format

Each `track.json` should include at minimum:

```json
{
  "title": "Automate My Soldiers",
  "version": "1.0.0",
  "artist": "Swrv3r",
  "audio_url": "https://...",
  "bpm": 130,
  "key": "C minor",
  "lyrics_file": "lyrics.txt",
  "decoded_file": "decoded-lyrics.md",
  "tags": ["cypherpop", "trap", "code", "decentralized"]
}
```
You can also include optional fields:

cover_art_url

stems (as an object with links)

credits block

Why This Protocol Exists
Cypherpop is encrypted autobiography.
A whisper between nodes. A resistance to clarity.

It encodes emotional signal inside digital structure—tracks that behave like software, yet speak like art. It was created to:

Escape algorithmic homogenization

Create a new form of programmable narrative

Build a forkable music standard where each track is versionable, ownable, remixable

To understand the culture behind the code, read MANIFESTO.md and whitepaper.md

Get Involved
Fork this repo

Add your own track folders

Propose track schema improvements

Build visualization layers, remix engines, or frontends

Submit a pull request or run it as your own parallel node

This protocol is not centralized. It’s not even finished. It’s alive.

Fork the protocol. Encrypt your signal.
Let the code sing.
