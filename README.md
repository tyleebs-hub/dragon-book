# Dragon Book (working title)

A novel written with Claude Code, one chapter per session.

## How to use
1. Open this folder in Claude Code.
2. The big structural questions (bond rule, how Hob dies, series or single book) were settled on 2026-11-06 and are recorded in the bible and outline. Remaining open questions are listed at the bottom of `outline.md`.
3. Then: "Write chapter 1." Claude reads the bible, outline, and continuity log, writes the chapter, and updates the log.
4. Review, edit, and commit after each chapter:
   ```
   git add -A && git commit -m "Ch 01 draft"
   ```
5. Every few chapters: "Do a continuity pass on chapters 1 to 5."

## Files
- `CLAUDE.md`: standing rules Claude follows every session (voice, style, process).
- `bible/`: the source of truth for characters, world, magic, and dragons.
- `outline.md`: chapter beats and structural open questions.
- `continuity.md`: what has actually happened in the prose so far.
- `chapters/`: the manuscript.
- `notes/`: the author's original notes, kept unchanged.
