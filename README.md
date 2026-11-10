# Calliope of Possible Futures

A slow emergent generative steam calliope in 15/16 that does not feel like 15/16.

- 9 pinned wheels in 3 banks (melody / bass / harmony); only 3 are loaded at a time.
- Melody and bass are the frame and never play the major/minor-deciding third note;
  the harmony wheel is the lens (Sun = major, Shade = minor, Re-root = relative minor 7).
- Because the wheels are cylinders, upcoming notes and the possible futures at each
  seam are displayed live, with the live probability of stay / swap / Mobius-flip.
- A boiler-pressure carry builds bar by bar and forces slow, syrupy changes at seams;
  swapped wheels crossfade in over a full cycle; after a change the machine locks 6 bars.
- Chord ring is 16 bars with fake resolutions at bars 4, 8, 12; 15/16 grouped 4+4+4+3
  lands one sixteenth early each bar so it keeps seeming about to resolve in 4.

Plain static page served by a tiny Python server (`server.py`, uses `$PORT`).
Run locally: `python3 server.py` then open http://localhost:8080

Proof of concept: all notes are guessed and disposable.
