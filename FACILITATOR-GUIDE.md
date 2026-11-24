# 🎤 Facilitator Guide — Vibathon (11:00–11:40)

## Before the day (do all of these)

- [ ] **Dry run on an attendee-style laptop** (no Git installed): open the Copilot app, sign in, start a session in an empty folder, run the starter prompt, open `index.html`. Time it.
- [ ] Confirm every attendee has a **GitHub account with Copilot access** and the app installed + signed in. Send install/sign-in instructions the day before.
- [ ] Confirm the app lets you pick a **plain local folder** without Git. If it insists on a repo, plan for attendees to pair with someone whose setup works.
- [ ] Share this repo link (or print `ATTENDEE-HANDOUT.md` + `prompts/`) so prompts are copy-paste ready.
- [ ] Have `fallback/index.html` downloaded locally — open it once in a browser to check it works.
- [ ] Test the room Wi-Fi with several machines at once; have a phone hotspot as backup.
- [ ] Set screen font/zoom large enough to read from the back.

## On the day — 10:45

- [ ] Copilot app open, signed in, empty folder `vibathon-live` on Desktop
- [ ] Starter prompt in clipboard
- [ ] Browser tab with `fallback/index.html` open (hidden)
- [ ] Handout link / QR code on a slide

---

## Run of show

### 11:00–11:04 · Set the challenge (4 min)
**Say:**
> "In the next 40 minutes, every one of you will build a working sales tool — without writing code. Your job isn't to code. Your job is what you already do every day: be clear about what you want, look at the result, and push back."

Briefly show the finished fallback dashboard: *"This is where we're heading."*

### 11:04–11:12 · Live build (8 min)
1. In the Copilot app, start a new session in the `vibathon-live` folder.
2. Paste the **starter prompt**. Read the first line out loud.
3. While it works, narrate:
   - "It's planning first — like a good engineer would."
   - "Notice I described the *outcome*, constraints, and audience — like a good brief."
4. When done, open `index.html` from the folder. Click the filter, add a deal.

**If it's slow (>4 min):** "While it finishes, here's one I made earlier" → switch to the fallback tab.

### 11:12–11:16 · One change from the room (4 min)
**Ask:** "What would make this more useful for your team?"
Take one idea, type it in plain words, refresh the browser.
**Say:** "First version is a draft. The value is in how fast you can iterate."

### 11:16–11:30 · Their turn (14 min)
- Point to the handout. Steps: empty folder → starter prompt → open `index.html` → pick **2 play prompts**.
- Walk the room. Pair anyone with setup trouble with a neighbor — don't debug laptops live.
- At 11:27: "Three minutes — pick your favorite change to show."

### 11:30–11:37 · Show & tell (7 min)
Ask for 3 volunteers (look for: most useful, most creative, funniest). 1–2 min each: "What did you ask for, and what did you get?"

### 11:37–11:40 · Land the message (3 min)
**Say:**
> "You supplied the goal, the judgment, and the feedback. Copilot did the implementation. That's the shift: the people who understand the business problem can now shape the solution directly — and developers move from typing code to reviewing and directing it."

Key takeaways for customer conversations:
1. **Speed:** idea → working prototype in minutes.
2. **Accessibility:** the skill is clear communication, not syntax.
3. **Human in the loop:** you review, test, and decide — AI doesn't ship on its own.
4. **Real teams** use the same loop on real codebases, with Git, reviews, and security controls.

---

## Troubleshooting cheat sheet

| Problem | Fix |
|---|---|
| Can't sign in / no Copilot access | Pair with a neighbor |
| App asks for a Git repo | Skip/decline; if blocked, pair up |
| Copilot asks permission to create files | Click **Allow** |
| Can't find `index.html` | Ask Copilot: *"Where did you save the file?"* |
| Change doesn't appear | Refresh the browser (⌘R / Ctrl+R) |
| Something broke | Tell Copilot: *"That broke the page — undo your last change."* |
| Wi-Fi dies | Show `fallback/index.html`, demo play prompts on your machine only |

## Safety reminders to say out loud
- Fictional data only — no real customer, deal, or personal info in prompts.
- This is a prototype exercise; production apps go through review, testing, and security checks.
