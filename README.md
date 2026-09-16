# 10704-group7-project (Project Pennsylvania)

CEN3031 Software Engineering, Fall 2026, University of Florida.

A web application that converts recorded audio (WAV, MP3, or a microphone recording) into a standard MIDI file. The backend detects note onsets, pitch, duration, and velocity and builds a `.mid` file. The frontend shows a piano-roll preview and plays the result back before download.

## Team

| Member | Role |
|---|---|
| Daniel Tiagi | Scrum Master / QA Lead |
| Brady O'Connor | Backend Lead |
| Vincent Schifano | Frontend Lead |

All three members work across the full stack. Lead roles indicate ownership and final say for that area.

## Repository layout

```
backend/    Python 3.12 transcription pipeline and FastAPI service
frontend/   React + Vite web interface
.github/    CI workflow and pull request template
```

## Tech stack

Python 3.12, librosa, basic-pitch, crepe, mido / pretty_midi, FastAPI + Uvicorn, pytest, React + Vite, html-midi-player. Everything is free and open source.

## Roadmap

- Phase 1 (MVP): monophonic transcription for voice, lead guitar, and single-line piano
- Phase 2: polyphonic transcription with basic-pitch, tempo and key estimation

## Workflow

- `main` is protected. All changes go through a pull request with at least one approving review and a passing CI run.
- Branch names: `feature/<short-description>`, `fix/<short-description>`, `chore/<short-description>`.
- Work is tracked on the GitHub Projects board. Every PR should link the issue it closes.
- Sprints are two weeks. Daniel runs planning and retrospectives.

See `CONTRIBUTING.md` for setup and PR steps.
