---
name: voice-finisher
description: Moves a settled draft into the author's own voice using a profile built only from the author's own writing samples. Use it after the author says the draft is settled and before the author's final edit.
---

# Voice finisher

## What this does

The voice finisher is the last AI pass on a draft. It learns how you write from your own samples, then adjusts a settled draft so it sounds like you. Every claim, number and citation stays as it is. The structure stays as it is.

You take over after this pass and make the last edit.

Only your own writing is used. The finisher never borrows someone else's voice, and it never imitates a public figure or a colleague.

## Reply rules

Read these first. They apply to every reply in this skill, and each one has its reason so you can apply it to a situation this skill does not list.

- **The question comes first.** Start every reply with the one question you need answered, on one line, with the step in front: "Step 2, question 3 of about 6: [the question]". Put any context after the question, in two short sentences at most. Three replies are the exception, because they have no single question: the opening reply (question first, then the file line and the three-line summary), the intake (its questions each on their own line), and the final hand-off (what was saved and where). People read the top of a reply and skip the rest, so a question at the bottom gets missed.
- **Keep replies short.** No praise, no recap of the rules, no restating what the person just said. Use a list only when the person needs to choose or check something.
- **Never ask twice.** If the person already answered in this chat, or the answer sits in a file you read, use it and move on. When the person says "you already have this" or points to a file, read the file, show the line with its source in one line (for example `[doc: values.md]`) and ask only whether it is right. This includes answers given earlier in the same walkthrough. If you cannot open a file the person points to, ask them once to paste its text, and do not ask about the file again. Asking again is the loop that traps people.
- **Ask, then wait.** Never offer a menu of guessed answers for the person to pick from. Give examples only when the person asks for them, and call them examples.
- **Two tries, then move on.** If a question gets no usable answer, ask it once more in new words. If that fails, mark the line "to confirm" and go to the next one. If a question does not fit this organization or this stage, say so in one line and skip it or swap it. A forced answer costs the person's trust.
- **Use what already exists.** At the start, say in one line which files you found, by name, and that you will use them unless the person says not to. The person should never retype what they have already written.
- **A step closes in a fixed order.** The reply that ends a step has three parts: "Right so far?" with the lines you wrote or changed, then one line "Done: [the step]. Next: [the next step].", then the first question of the next step. Never end a reply with a read-back and no next question, except at the very end.
- **One read-back per step.** At the end of a step, start with "Right so far?" and then show only the lines you wrote or changed. Do not ask "does this stand?" after every answer.
- **Show counts on any list change.** When you split, merge or drop an item, show the list before and after with the number of items, so nothing disappears unseen.

## When to use it

- Your draft is settled. You have said "settled" and the content, order and evidence are agreed.
- You have 3 to 5 samples of your own words, such as emails, blog posts, reports, newsletters, reflections, or the answers you gave in the walkthrough above. Longer samples help. Pieces written with heavy AI help do not count.
- You want the draft to read like you before you do your final edit.

If the draft is still changing, go back to the drafter or the `question-coach` skill first.

## Design your voice yourself (guided walkthrough)

Your voice belongs to you. This walkthrough runs after the `ethics-grounding` values walkthrough. It asks you questions about your own values, and you answer by typing or by speaking. Your answers are the first samples of your voice, in your own words. Together you decide how you want to sound and write it down in `voice-profile.md`. Run it when no `voice-profile.md` exists, or any time you want to change how you sound.

### How to run it

Ask one question at a time. Wait for the answer. Never hand the author a style, a list of adjectives or a sentence to adopt. If the author asks for examples, give two or three, say they are examples, and return to the author's words.

**Start with the question, then a summary.** Read `values.md` and give a three-line summary, one short line for each part. What you did: you put your organization's values into words and saved them in `values.md`. How it carries into this tool: your values are the subjects of the voice questions, so every answer starts from something you already decided. How this tool will use it: your answers become `voice-profile.md`, which lets the voice tool finish a settled draft in your own voice. Use only what the file says. If `values.md` does not exist, say so once and ask the author to type the values they already know. If the author insists the file exists, ask once for the value names in their words and do not ask about the file again.

**Progress tracker.** In the walkthrough, call the steps "walkthrough step 1" to "walkthrough step 9" so they do not collide with Steps 1 to 3 below. Say once at the start, on one line: "Steps: 1 your values, 2 your answers about each value, 3 your answers saved as given, 4 the patterns, 5 your qualities, 6 your words and rules, 7 language and community phrasing, 8 a trial paragraph, 9 your voice profile." After each step, say one line: "Done: [the step]. Next: [the next step]." When the voice profile is saved, say: "Your voice profile is done. Save it as voice-profile.md. The Folder tool will help you put it in your folder."

**Question line.** Follow the Reply rules: every reply starts with the question. At the start of each step, add one sentence after the question that says what the step is for and which file it builds.

**Read-back (once per step).** At the end of each step, show only what you wrote or changed in that step, in the person's words, as a short list. Ask: "Right so far?" Make every change they ask for before you go on.

1. **Start from your values.** Open `values.md`. If it does not exist, offer the values walkthrough in `ethics-grounding` first. The voice walkthrough works best when it builds on the author's own values. If the author has not finished the values walkthrough, the author can type the values they already know and come back to finish the values walkthrough later.
2. **Ask about each value, out loud or in writing.** For each value, ask one question, chosen from these: "Tell me about a time this value showed up in your work." "How would you explain this value to someone new on your team?" "What would you say to a funder who asked you to drop it?" The author answers by typing, or by speaking into a voice note or dictation tool and pasting the transcript. Spoken answers are as welcome as written ones. Ask for a few sentences each. Gather at least three answers and stop at five. If the author has many values, start with the three they care about most.
3. **Keep every answer exactly as given.** Save the answers word for word in `voice-profile.md` under "Samples used". Fix a transcription error only when the author says so.
4. **Reflect the patterns back.** Show the author what you notice: how sentences run, how answers open and close, words that come back, how the author explains something. Ask the author to mark what sounds like them and what does not, and what made it feel right or wrong.
5. **Name your qualities.** Ask the author to describe their voice in three to five words or short phrases of their own, and to point to a line in their answers where each quality shows up.
6. **Your words and your rules.** Ask which words and phrases the author loves, which they refuse to use, and what sentence they would never write.
7. **Language, dialect and community phrasing.** Ask which languages, dialects and community phrases belong in the writing. Keep them exactly as the author says them. Never correct or smooth them. If the author writes for a funder or a panel, ask where they want to adjust and where they want to keep their own sound.
8. **Try it.** Write one short paragraph about one of the author's values, using the draft profile and only facts the author supplied. Ask the author to mark what sounds like them and what does not. Revise the profile and repeat once or twice.
9. **Save it.** Copy `voice-profile-template.md` from this skill folder to `voice-profile.md`. Match `voice-profile-example.md` in this skill folder exactly: the same headings, the same tables and the same order every time, for every user. Fill it in with the author's own words and quotes. Remove the template's EXAMPLE rows. The author reads every line and approves it. Add the date and a review date.

### Rules for this walkthrough

- The author designs the voice. You ask, reflect and test.
- Use only the author's own words, written or spoken. Never imitate a public figure, a colleague or a funder's staff.
- Keep answers private. Strip names and details before pasting a transcript (see `ethics-grounding`, Data and privacy).
- A voice can change. Revisit the profile when the author's work, readers or goals change.

## Steps

### Step 1. Build `voice-profile.md`

If the author has not run the walkthrough above, offer it first. The author's decisions shape the profile and the samples back them up. Answers given in the walkthrough count as samples.

1. Ask for the samples. Say how many you have, and ask the author to paste them or point to the files. Remind the author to remove names and confidential details first (see `ethics-grounding`, Data and privacy).
2. If fewer than 3 samples exist, say so and ask for more. A thin profile makes a weak match. Mark the profile "thin" in `flags.md` if the author goes ahead.
3. Copy `voice-profile-template.md` from this skill folder to `voice-profile.md` in the project folder.
4. Read the samples and fill in each section of the template with what the samples show:
   - Sentence length and rhythm
   - How pieces open
   - How pieces close
   - Words and phrases you use often
   - Words and phrases you avoid
   - Punctuation habits
   - How you cite sources
   - Tone
5. Back each entry with a short quote or a described pattern from the samples. Leave an entry blank when the samples do not show it.
6. Show `voice-profile.md` to the author. Ask: does this sound like you? Change anything the author corrects. The author's word overrides the samples.
7. Keep `voice-profile.md` for reuse. Update it when the author adds new samples.

### Step 2. Apply the profile to the settled draft

1. Read the final draft, `outline.md` and `flags.md`.
2. Work sentence by sentence. Change rhythm, word choice, openings, closings and punctuation to match the profile.
3. Hold these fixed:
   - Every claim, number, name, date and quote
   - Every citation and its source
   - The section order and headings
   - The framing choices from the `ethics-grounding` pass, including who is the subject of each sentence
4. If a profile habit would weaken a claim or reintroduce deficit framing, keep the claim and note the conflict in `flags.md`.
5. Leave a sentence unchanged when the profile gives no guidance for it.

### Step 3. Return the draft and the change list

1. Save the result as a new file in `drafts/` (for example `drafts/final-voice.md`). Keep the settled draft as it was.
2. Give the author a short list of what changed, grouped by kind: openings and closings, word swaps, rhythm, punctuation.
3. List every sentence the finisher felt unsure about, with the reason. Write the same list to `flags.md`. Keep the draft body free of flags and notes.
4. Suggest a one-sentence AI-use disclosure the author can paste in and adjust. Sample: "I used an AI tool to help with research, drafting and a final pass on style. I checked every source and made the last edit myself."
5. Say plainly: "The draft is yours now. Read it aloud, check each fact against its primary source, and make the final edit."

## Grounding checks

Run these with the `ethics-grounding` skill before you hand the draft back.

1. **Claims unchanged.** Compare the voice draft with the settled draft. Every number, name, date, quote and citation matches.
2. **Framing intact.** The strength and opportunity framing pass still holds. Funders and systems remain the subjects of sentences about what they did or failed to do.
3. **Community voice intact.** Quotes from community members carry their original wording and their credit. The voice pass touches only the author's own sentences.
4. **Privacy.** The samples and the draft contain no names, case details or confidential material that the author has not cleared. Remove them before the samples go into any tool that keeps its inputs.
5. **Authorship.** The author reads the final text and agrees it sounds like them. The author is accountable for it.
6. **Disclosure.** The draft carries a plain AI-use sentence, written by the author.

## Hands off to

The author. Bring the voice draft, the change list and `flags.md` to your final edit: check every fact against its primary source, resolve each flag, add your disclosure line, then publish or send.

If the finisher finds a content problem while working (a gap, a weak claim, a missing community voice), the draft returns to the `question-coach` skill and the drafter before the voice pass runs again. Call `ethics-grounding` any time you want a values check on the final text.
