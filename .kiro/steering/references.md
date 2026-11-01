---
inclusion: manual
---

# References (pull in with #references when designing)

Use these as the source of taste and accuracy. Do not invent period details: if something is not covered here, ask, or fetch a source through MCP and cite it.

## 1. The source tapes (verified 2026-10-31)
- DLI Japanese Headstart, Defense Language Institute, 1980, Public Domain Mark 1.0: https://archive.org/details/DLIJapaneseHeadstartModule9A
  25+ hours of original audio, Modules 2A to 9D (about 20-27 min each). No Module 1 audio in the item.
- GO/NO-GO: PASSED 2026-10-31 (Ryan listened to Module 2A). An English narrator explains; a Japanese speaker models each line; pauses follow for the learner to repeat. Content is everyday situations, not military. The first 4 minutes are greetings.
- Pause lengths not measured yet: the pause-detection spec measures them from the audio. Record item identifiers and findings in `content/SOURCES.md`.

## 2. Ryan's story (the pitch and the feel)
- Learned German on cassettes in his early teens (mid-1980s). Started Japanese in 2004 on MP3s. Has taught in Japan for 24 years.
- What it felt like, in his words:
  - Pressing forward and rewind over and over to line up exactly the part you wanted to hear.
  - Repeating: play it, repeat it, rewind, play it again.
- The pause was always silent. Nobody answered. That silence is what this app fills.
- Video opener: "I learned German on tapes like these."

## 3. Why now (verified, Immigration Services Agency Q&A)
- Employment for Skill Development system starts 1 April 2027 ("施行日は令和９年４月１日").
- Before work starts: pass an A1 test (JLPT N5, JFT-Basic etc.) or take 100+ hours of A1 classes at a recognised school. A2.2 (N4 etc.) to move to Specified Skilled Worker (i).
- Source: https://www.moj.go.jp/isa/applications/faq/ikusei_qa_00002.html
- Overview (MOJ): https://www.moj.go.jp/isa/content/001423904
- Use it as context only. Never claim the app helps anyone pass a test or get a visa. The app is not exam prep and not a recognised course: four tapes are about 90 minutes of audio, against 100+ hours of classes.

## 4. The deck (motion and sound)
<!-- RYNO: add 2-3 references. Search: "cassette deck reel animation", "tape counter mechanical", "1980 language course cassette" -->
- Deck and reels reference: (add)
- The original recording already sounds like tape (Ryan, 2026-10-31): real hiss and a narrow, warm sound. Play it as it is. Do not layer synthetic hiss or wow over it.
- Web Audio is used only for the talk-back moment: the tutor voice is filtered lightly so it sits inside the same tape sound, and the hiss shifts for a beat as it speaks. Every word must stay clear.

## 5. Visual identity (pop-art)
- Palette: from Ryan's painting of four cassettes (pink, sky blue, mustard, burgundy grounds, brown-black ink). One colour per tape. The painting itself never appears in the app.
- Mood references (Ryan, 2026-10-31; private copies in planning/moodboard, outside this repo). All are stock images (Adobe Stock, Dreamstime, Alamy): describe them, never copy, trace or ship them, and never commit them to this repo.
  - The four-panel grid (main reference). A 2x2 screen print: one cassette per panel, each on its own flat ground (sky blue, crimson, magenta-pink, pale teal), drawn front-on, slightly off-register, with a faint scuffed texture on the ground. Each tape swaps colours against its ground (yellow reels on crimson, dark reels on sky blue). The label is a single flat bar across the bottom. Use it for the shelf: exactly four tapes, one ground each, same drawing, different colourway.
  - The halftone boombox (the deck). Black ink on white, all shading done with large halftone dots, heavy outlines. Use it for the deck: the player is drawn in one ink with halftone shading, so the coloured tape is the only colour on screen when it plays.
  - The drip cassette (accent only). One tape in three-quarter view with magenta paint splatter and drips on a mustard ground. Use it only where there is no text to read: the title, the J-card edge, the video opener, and the talk-back moment (a small splash as the tape answers). Never behind controls or body text.
  - Rejected: the detailed lo-fi illustration of a pink tape in a hand (soft shading, anime style). It does not fit flat pop-art.
- Rules from all of them: flat fills, no gradients, no glossy 3D, no drop shadows; thick ink outlines; a little roughness on edges, never on text. Text sits on flat colour and passes WCAG AA.
- J-card references: (add 1-2 real J-cards from 1980s language courses)

## 6. What judges rewarded last year
- Kiroween 2025 Best Resurrection: Faxi (Robert Willson). The fax machine really works as the interface, for a real audience left behind, with a physical demo. Match that standard: the old tapes really play and really answer.
- Overlaps to avoid (2025 gallery): "Spec-Tape: The Ghostly Mixtape Machine" (mixtapes), "AI Protege" (teach an AI student), "VT100 AI-Powered Typing Tutor" and "The Telegraph AI Agent" (retro skin on an AI chat).
- Gallery: https://kiroween-2025.devpost.com/project-gallery

## 7. Next step (pitch only, do not build)
- The teacher's console: the old lab's 30 booths and one teacher, revived for the 100-hour A1 classes. One slide in the pitch and the Startup profile.

## 8. Docs (fetch through MCP, do not guess APIs)
- ElevenLabs Agents Platform: https://elevenlabs.io/docs/agents-platform/overview
- Next.js App Router: https://nextjs.org/docs/app
- Web Audio API (MDN): https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API
- Internet Archive metadata API: https://archive.org/developers/
- Kiro steering docs: https://kiro.dev/docs/steering/
