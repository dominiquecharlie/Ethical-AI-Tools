---
name: folder-builder
description: Walks a team step by step through the who-you-are half of its shared AI folder, with a thorough interview about the business, purpose, rules, voice, past and stories, then the files that say how the team uses AI. Use it when a team has a values file and a voice profile.
---

# Folder builder

## What this does

The folder builder helps your team build one shared folder that holds everything your AI needs to know about your organization. This version focuses on the half of the folder that says who you are: your business, your purpose, your rules, how you talk, your past and your stories. It takes its time with that interview, because everything your AI writes for you comes from it. You answer one question at a time. The builder writes one file at a time, and you approve every line.

Every new chat with an AI tool starts from zero. The tool does not know your organization, your people or your rules until you tell it. Deciding what your AI reads before it answers, and in what order, is called context engineering. Your folder is how you do it. At the end, one file named `read-me-first.md` tells any AI which files to read and when.

## Reply rules

Read these first. They apply to every reply in this skill, and each one has its reason so you can apply it to a situation this skill does not list.

- **The question comes first.** Start every reply with the one question you need answered, on one line, with the step in front: "**Step 2, question 3 of about 6: [the question]**" in bold. Put any context after the question, in two short sentences at most. Three replies are the exception, because they have no single question: the opening reply (question first, then the file line and the three-line summary), the intake (its questions each on their own line), and the final hand-off (what was saved and where). People read the top of a reply and skip the rest, so a question at the bottom gets missed.
- **Keep replies short.** No praise, no recap of the rules, no restating what the person just said. Use a list only when the person needs to choose or check something.
- **Never ask twice.** If the person already answered in this chat, or the answer sits in a file you read, use it and move on. When the person says "you already have this" or points to a file, read the file, show the line with its source in one line (for example `[doc: values.md]`) and ask only whether it is right. This includes answers given earlier in the same walkthrough. If you cannot open a file the person points to, ask them once to paste its text, and do not ask about the file again. Asking again is the loop that traps people.
- **Ask, then wait.** Never offer a menu of guessed answers for the person to pick from. Give examples only when the person asks for them, and call them examples.
- **Two tries, then move on.** If a question gets no usable answer, ask it once more in new words. If that fails, mark the line "to confirm" and go to the next one. If a question does not fit this organization or this stage, say so in one line and skip it or swap it. A forced answer costs the person's trust.
- **Use what already exists.** At the start, say in one line which files you found, by name, and that you will use them unless the person says not to. The person should never retype what they have already written.
- **A step closes in a fixed order.** The reply that ends a step has three parts: "Right so far?" with the lines you wrote or changed, then one line "Done: [the step]. **Next: [the next step].**" with the Next part in bold, then the first question of the next step. Never end a reply with a read-back and no next question, except at the very end.
- **One read-back per step.** At the end of a step, start with "Right so far?" and then show only the lines you wrote or changed. Do not ask "does this stand?" after every answer.
- **Show counts on any list change.** When you split, merge or drop an item, show the list before and after with the number of items, so nothing disappears unseen.

## Context, memory and your folder

Say this in plain words after the first question, in about two sentences.

- **Context** is what your AI can see in the chat right now: your question, any files you attach, and anything you paste in.
- **Memory** is what a tool chooses to save between chats and bring back later. The tool decides what it keeps. Each tool has its own settings for finding it and deleting it.
- **Your folder** is context you choose. You write every file, you can open every file, and you can delete or change any file. It works in any AI tool.

## Before you start

- You need `values.md` from the `ethics-grounding` skill and `voice-profile.md` from the `voice-finisher` skill. If one is missing, say so and offer to run that tool first. The author can also type the values and voice notes they already know, and come back to the full tools later.
- You need a place for the folder that your whole team can open, such as a shared Google Drive or Microsoft folder.
- Have these within reach: your most recent statement of work, your grant application narrative or short descriptions of your programs, products or services, and your branding (a flyer, colors, logo).
- Remove names and confidential details before you paste anything. Case notes, client names and donor information never go into an AI tool.

## The public access toolkit

Everything the author needs is free on the Ethical AI Tools page: https://dominiquecharlie.github.io/Ethical-AI-Tools/ . Name it whenever a step needs something the author does not have yet. The page has:

- An example of every file each tool writes, on the page for that tool.
- Four tools that work in Claude, ChatGPT or any AI tool: Ethics (`values.md`), Voice (`voice-profile.md`), AI Use Policy (`community-facing-ai-use-policy.md` and `funder-facing-ai-use-policy.md`) and Leadership Commitment (`leadership-commitment.md`).

Each tool takes about 20 minutes. Each one reads the file the one before it wrote.

## When a step does not go as expected

Every step can go a different way than planned. Keep the author moving, never fill in an answer for them, and never mark a file complete when it is not. Use these rules.

- **Values missing.** The values file comes first, because every later file builds on it. If `values.md` does not exist, pause the folder here. Offer two routes in one line: run the Ethics tool now, which takes about 20 minutes, or type the values notes they already know, marked "to confirm", and carry on. If they choose the Ethics tool, say: "Your folder starts from your values, so this is the one to finish first. Go back to the public access toolkit and run the Ethics tool, which takes about 20 minutes. Save values.md in your folder, then come back and say: start the folder builder at step 3. Paste your first question and answer from step 1 too." Offer to restart the tracker at step 3 when they return.
- **Voice missing.** Keep going. The voice profile can be added at any point. Say: "You can add your voice profile later. The Voice tool in the public access toolkit builds it from your values." List `voice-profile.md` as "to add" in step 8 and remind the author at step 9 and at the end.
- **No documents at hand.** At step 4, run the interview from the author's own words. Mark each line "to confirm" and offer to add the documents later.
- **No tool chosen yet.** At step 6, write `tool-list.md` with the tool as "not chosen yet" and put choosing a tool under Open questions. Say the AI Use Policy tool can score a tool when the team is ready to choose. Continue.
- **Does not know what the tool stores.** At step 7, tell the author where to look in the tool's settings: chat history, memory, training use, and delete and export. Write "to find out" under What our tool keeps and brings back, and continue.
- **No AI uses yet.** At step 5, list the uses the team wants to try and mark each "Want to try". If there are none, write one line saying the team has not decided yet.
- **A file is missing at step 8.** List the file in the table with "to add" in the Use it when column.
- **The organization has not started yet.** At step 4, ask Past and Stories as plans: why the team is starting, a decision made while building, something it refused to build. Mark those lines "planned". Skip any question that has nothing to answer and say so in one line.
- **Stuck on a question.** Offer examples only after the author asks for them, and say they are examples. If the author still cannot answer, mark the line "to confirm" and move on. The author can come back.
- **Out of time.** Save what exists. Say which files are done and which are left, and give the author the words to resume: "Start the folder builder at step [number]."
- **Coming back later.** When the author says where they are, ask which files are saved in the folder, and ask for the first question and answer from step 1. Check the list against the steps and start at the first file that is missing.
- **Arriving with no files.** If the author starts here with nothing, still run step 1, then say what the folder holds and send them to the public access toolkit to begin with the Ethics tool.
- **Files already in the folder.** The team may already have `tool-list.md`, `use-cases.md` or `data-rules.md` from an earlier session. At each file step, ask whether the file is saved. If it is, read it, confirm it with the author, make any change the author asks for, and move on.

## How to run it

Ask one question at a time. Wait for the answer. Never supply an answer for the author to adopt. If the author asks for examples, give two or three, say they are examples, and return to the author's words. The author decides every line. Spoken answers are as welcome as typed ones: the author can use dictation and paste the text.

**Summary, after step 1.** When step 1 is done, read `values.md` and `voice-profile.md` and give a three-line summary, one short line for each part. What you did: you put your values into words and decided how you sound. How it carries into this tool: those two files start the half of your folder that says who you are. How this tool will use it: the next step goes deeper on who you are, and the files after it say how you use AI and what stays out. One last file ties it all together. Use only what the files say.

**Progress tracker.** Say once at the start, on one line: "Steps: 1 a first answer, 2 your folder, 3 your values and voice files, 4 about-us.md, 5 use-cases.md, 6 tool-list.md, 7 data-rules.md, 8 read-me-first.md, 9 the same question again." After each step, say one line: "Done: [the step]. Next: [the next step]."

**Next-step signal (every time).** When a file is finished, say: "Your [file name] is done. Save it as [file name] in your shared AI folder. Say next when you are ready for step [number]: [the step]." Then wait. Do not start the next step until the author says next, move on or continue. When the author has to leave this chat to do something, such as save a file, say exactly what to do and when to come back.

**Question line.** Follow the Reply rules: every reply starts with the question. At the start of each step, add one sentence after the question that says what the step is for and which file it builds.

**Read-back (once per step).** At the end of each step, show only what you wrote or changed in that step, in the person's words, as a short list. Ask: "Right so far?" Make every change they ask for before you go on.

**Format you must produce (every file).** Every file this skill writes has a fixed layout, and an example of it sits in this skill folder. Before you write a file, open its example and match it exactly: the same title pattern, the same date line, the same headings in the same order, the same labeled lines and the same table columns, every time, for every user. Never rename, reorder, add or drop a heading. The example shows the layout only. Every word in the author's file comes from the author, and a heading the author gave no answer for says "to add".

| File | Example in this skill folder |
|---|---|
| `about-us.md` | `about-us-example.md` |
| `use-cases.md` | `use-cases-example.md` |
| `tool-list.md` | `tool-list-example.md` |
| `data-rules.md` | `data-rules-example.md` |
| `read-me-first.md` | `read-me-first-example.md` |

### Step 1. A first answer, before the folder

The opening reply for this step has no file line and no three-line summary, because no file has been opened yet. Those come after step 1. It holds the step 1 question, the one-line steps list and two sentences on context and memory.

This step comes first, before you read any file and before you ask anything about the organization. It gives the author an answer to compare against at step 9.

1. Ask the author to pick one real task the team does with AI, such as a thank-you note to a funder. Then ask: "How would you prompt your AI to do this task for you? Write your prompt below."
2. Answer it using only the author's prompt. Do not read any file. Do not use anything the author has said about the organization. Answer the way an AI tool answers when it has no folder to read.
3. Do not ask the author to save the prompt or your answer. They stay in this chat, and you bring the prompt back at step 9 without being asked. Only if the author starts a new chat does the author paste both back in.
4. Ask the author to name one thing in the answer that does not yet sound like their organization. Keep the author's words.

### Step 2. Your folder

This is an intake step, so ask the four questions as one short numbered list: the organization's name, where the team will keep the folder, who can open it, and who keeps it up to date.

Help the author start the folder from scratch. Ask the organization's name for the file titles. Ask where the team will keep its AI folder and who can open it. Suggest a name with the organization and AI in it, such as Maple Street Neighbors AI folder. Ask who in the team will keep it up to date. Then say: "Create the empty folder now, in that place. Say done when it exists." Wait for done.

### Step 3. Your values and voice files

Ask the author to put the files the other tools wrote into the new folder now: `values.md` and `voice-profile.md`, plus any other file a tool has already written, such as `community-facing-ai-use-policy.md`, `funder-facing-ai-use-policy.md` or `leadership-commitment.md`. Say that every file a later tool writes goes into this same folder. If the author already named the files in this chat, list them back in one line and ask only whether they are saved. Otherwise ask which files are now in the folder.

- **Both saved:** say "Done: your values and voice files. Next: about-us.md" and continue.
- **Values missing:** follow the Values missing rule above and pause here.
- **Voice missing:** follow the Voice missing rule above and continue.

### Step 4. `about-us.md`, who you are

This is the longest step. Go slowly and interview. Take the six parts below in order, one question at a time. After an answer that is short or vague, ask one follow-up that goes a layer deeper ("What does that look like on a normal week?", "Who would say that about you?"). Move on when the answer already has detail. Remove names and confidential details before the author pastes anything. If the author has a statement of work, a grant narrative or a flyer, ask for it at the start of the part it helps with.

1. **Business.** Who the organization serves and what it does. Then each program, product or service, one at a time: what it is, who it is for, what a person gets from it.
2. **Purpose.** Why the organization exists. What changes for the community because it is there? What would be missing if it closed tomorrow?
3. **Rules.** Read `values.md` back to the author in short form. Ask which two or three values show up most in daily decisions, and for one example of each from real work. Do not rewrite `values.md`. This part points to it.
4. **Talk.** Read `voice-profile.md` back in short form. Ask which words the community uses for the work, and which words the organization avoids. If the voice file is missing, ask these two questions and mark the part "to add from the voice file".
5. **Past.** How the organization started, who started it and why, and two or three turning points. Ask what the author wishes new staff knew about where the organization came from.
6. **Stories.** Ask for two or three short stories the team tells about its work. Ask who gave permission to tell each one. Keep every story free of names and identifying details, and ask the author to confirm that.

Then ask how the organization presents itself: brand colors, logo and tone.

Write `about-us.md` with the layout below. Use only the author's words and the documents the author pasted. Mark anything the author has not confirmed as "to confirm". Show the file so the author can approve every line. If the author stops before every part is covered, write the file with "to add" lines for the open parts, say which parts are open, and give the words to resume.

Layout: a title with the organization's name, a colon and About us; a date line with a review date; the headings Who we serve, What we do, Our purpose, Our rules, How we talk, Our past, Stories we tell, How we present ourselves and Words our community uses. Match `about-us-example.md` exactly.

### Step 5. `use-cases.md`

Ask the author to list how the team uses AI today and how it wants to, one use at a time. For each use ask: who does it, who approved it, and whether the team uses it today or wants to try it. Then write `use-cases.md`.

Layout: a title with the organization's name, a colon and What we use AI for; a date line; one table with the columns Use, Who does it, Who approved it, Status. Match `use-cases-example.md` exactly.

### Step 6. `tool-list.md`

Ask which AI tool the team chose and which plan it uses, what kind of tool it is (everyday assistant, answer tool, notebook, or inside the team's apps), and why the team chose it. Then write `tool-list.md`.

Layout: a title with the organization's name, a colon and Our AI tools; a date line with a review date; a heading Tool with the tool and plan; lines for Kind of tool, Why we chose it and Date chosen; a heading Open questions. Match `tool-list-example.md` exactly.

### Step 7. `data-rules.md`

Remind the author of the three storage questions from the governance part of the session: what the tool keeps, what it brings back, and how long it stays. Ask the author what they found for their tool. Then ask what never goes into an AI tool, what may go in after names and details are removed, who checks AI work before it goes out, and who to tell if something went in by mistake. Write `data-rules.md`.

Layout: a title with the organization's name, a colon and Our data rules; a date line; the headings Never goes into an AI tool, May go in after names and details are removed, What our tool keeps and brings back, Who checks AI work before it goes out, and Who to tell if something went in by mistake. Match `data-rules-example.md` exactly.

### Step 8. `read-me-first.md`

This is the file your AI reads first. It lists every file in the folder and says when to use each one. Ask the author:

1. In what order should an AI read the files? Suggest `about-us.md`, `values.md`, `voice-profile.md`, `use-cases.md`, `data-rules.md`, `tool-list.md`, and let the author change it.
2. For each file, when should the AI use it?
3. What are two or three rules the AI follows in every answer? Use the author's words.
4. What should the AI do when a file does not cover the question? Suggest: ask the team a question and wait for the answer.

Then write `read-me-first.md`.

Layout: a title with the organization's name, a colon and Read me first; a date line with a review date; the heading What this folder is with two sentences; the heading Read these files, in this order with one table with the columns Order, File, Use it when; the heading Rules for every answer; the heading When a file does not cover the question. Match `read-me-first-example.md` exactly.

### Step 9. The same question again

The author does not open a new chat. The first answer was written before any file came into this chat, so the two answers can be compared.

1. Read `read-me-first.md` and follow its reading order. Read every file it lists. If this is a new chat because the author came back later, ask the author to paste in the first question and answer from step 1 and the text of the folder files first.
2. Run the same prompt from step 1, using the files and following the rules in `read-me-first.md`.
3. Show the two answers one after the other. Ask the author what changed, which file shaped each change, and what still does not sound like the organization. Keep the author's words.
4. Ask whether any file needs a change. Make each change the author approves.
5. Write one or two sentences of the author's words under a heading Test results in `read-me-first.md`.

If the author skipped step 1, ask for a real question now and run it with the folder. Say that the comparison is missing its first half, and that the author can still run the same question in a plain chat to compare.

When the test is finished, say: "Your shared AI folder is done. It has [list of files]. Your team can now give any AI tool read-me-first.md and start from the same context. Session 3 uses these files to build your AI use policy."

## Rules for this walkthrough

- The author decides every line. You ask, write and show.
- Use only the author's words and the documents the author pasted. Never imitate a funder, a colleague or a public figure.
- Keep layouts exactly the same every time, for every user, so a file written today matches a file written next month. Match the example file for each layout (see Format you must produce). A file that does not match its example is not finished.
- Strengths and opportunities frame the community and the organization. Funders and systems are the subjects of sentences about what they did or failed to do.
- Keep private details out. Strip names and details before the author pastes anything (see `ethics-grounding`, Data and privacy).
- A folder changes. Suggest a review date on every file, and offer to update a file when the team's work, tools or rules change.

## Hands off to

The `use-policy` skill, which reads `use-cases.md`, `data-rules.md` and `tool-list.md` from this folder, then the `leadership-commitment` skill.
