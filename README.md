# Cypherpop Protocol

**Cypherpop** is a cultural operating system disguised as a genre.

It is a remixable protocol for encoded music, programmable meaning, and decentralized artistry.  
This repository contains the living documentation, templates, submission logic, and value system for building Cypherpop-compliant track capsules.

---

## What’s in This Repo

| File / Folder              | Purpose                                                                 |
|----------------------------|-------------------------------------------------------------------------|
| `10_COMMITS.md`            | The protocol’s ethic layer — 10 executable principles that define Cypherpop |
| `CYPHERPOP_PROTOCOL_PRIMER.md` | The philosophy, process, and structure behind the protocol             |
| `whitepaper.md`            | Deep dive into genre mechanics, aesthetic logic, and cultural roots      |
| `cyphernary.md`            | Living glossary of key terms, symbolic logic, and protocol slang         |
| `CHANGELOG.md`             | Version history of the protocol and architecture                         |
| `LICENSE`                  | MIT license — remix-friendly and permissionless                          |
| `tracks/`                  | All verified Cypherpop tracks with full metadata and decoded insight     |
| `starter-kits/`            | Templates, onboarding, and [submit.md](starter-kits/submit.md) instructions for artists |
| `README.md` (this)         | Start here. This is the entrypoint for contributing and understanding    |

---

## What Is a Cypherpop Track?

Each track is a fully self-contained folder:

```
tracks/
└── your-track-name/
    ├── README.md              # Short summary and notes about the track
    ├── lyrics.txt             # Raw lyrics
    ├── decoded-lyrics.md      # Symbolism, metaphors, code references
    └── track.json             # Structured metadata: title, version, bpm, etc.
```

You can optionally include:
- `cover.png` — visual art
- `stems/` — isolated audio files
- `manifest-snippet.json` — if auto-generating metadata for protocol use

---

## Get Started with a Track

1. **Download the [Starter Kit](starter-kits/track-template.zip)**  
2. **Rename the folder** to your track title (e.g. `tracks/automate-my-soldiers/`)  
3. **Fill in the required files**
4. **Host your `.mp3`** somewhere decentralized (Supabase, IPFS, Arweave, etc.)  
5. **Submit your folder via pull request**  
   → See: [Submit Instructions](starter-kits/submit.md)

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

You can also include:
- `cover_art_url`
- `stems` (as an object with audio links)
- `credits` (block for writer/producer/etc.)

---

## Why This Protocol Exists

Cypherpop is encrypted autobiography.  
A whisper between nodes. A resistance to clarity.

It encodes emotional signal inside digital structure—tracks that behave like software, yet speak like art.  
It was created to:

- Escape algorithmic homogenization  
- Create a new form of programmable narrative  
- Build a forkable music standard where each track is versionable, ownable, remixable

> To understand the ethic layer, read [`10_COMMITS.md`](./10_COMMITS.md)  
> To understand the methodology, read [`CYPHERPOP_PROTOCOL_PRIMER.md`](./CYPHERPOP_PROTOCOL_PRIMER.md)

---

## Get Involved

- Fork this repo  
- Add your own track folders  
- Propose protocol or schema improvements  
- Build visualizers, remix tools, or cultural frontends  
- Submit a pull request or fork the protocol and build your own node

> This protocol is not centralized.  
> It’s not even finished.  
> It’s alive.

**Fork the protocol. Encrypt your signal.  
Let the code sing.**
