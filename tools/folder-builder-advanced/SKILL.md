---
name: folder-builder-advanced
description: Walks a team that builds its own AI tools through its shared AI folder, one file at a time, with extra steps for what the tool takes in, what it makes and how it checks itself. Use it when a team has a values file and a voice profile and builds or configures AI for others.
---

# Folder builder, advanced

This version is for teams that build or configure AI tools for others. It follows the same steps as the `folder-builder` skill and adds three things in step 8: how your AI decides which files to read first, a check on every answer, and a rule for fixing the folder when something breaks.

## What this does

The folder builder helps your team build one shared folder that holds everything your AI needs to know about your organization. You answer one question at a time. The builder writes one file at a time, and you approve every line.

Every new chat with an AI tool starts from zero. The tool does not know your organization, your people or your rules until you tell it. Deciding what your AI reads before it answers, and in what order, is called context engineering. Your folder is how you do it. At the end, one file named `read-me-first.md` tells any AI which files to read and when.

## Context, memory and your folder

Say this in plain words at the start, in about four sentences.

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

- The Tool Audit sheet, for choosing a tool and reading its plan and settings.
- Four tools that work in Claude, ChatGPT or any AI tool: Ethics (`values.md`), Voice (`voice-profile.md`), AI Use Policy (`sorting.md` and `use-policy.md`) and Leadership Commitment (`leadership-commitment.md`).
- The Start your folder step, with a copyable prompt and example files.
- The Scenario Sorting sheet, which leads to the policy and leadership tools.

Each tool takes about 20 minutes. Each one reads the file the one before it wrote.

## When a step does not go as expected

Every step can go a different way than planned. Keep the author moving, never fill in an answer for them, and never mark a file complete when it is not. Use these rules.

- **Values missing.** The values file comes first, because every later file builds on it. If `values.md` does not exist, pause the folder here. Say: "Your folder starts from your values, so this is the one to finish first. Go back to the public access toolkit and run the Ethics tool, which takes about 20 minutes. Save values.md in your folder, then come back and say: start the folder builder at step 3. Paste your first question and answer from step 1 too." Offer to restart the tracker at step 3 when they return.
- **Voice missing.** Keep going. The voice profile can be added at any point. Say: "You can add your voice profile later. The Voice tool in the public access toolkit builds it from your values." List `voice-profile.md` as "to add" in step 8 and remind the author at step 9 and at the end.
- **No documents at hand.** At step 4, ask the author to describe the organization in their own words. Mark each line "to confirm" and offer to add the documents later.
- **No tool chosen yet.** At step 6, point to the Tool Audit sheet in the toolkit, which also helps compare vendors and models. Write `tool-list.md` with the tool as "not chosen yet" and put the audit under Open questions. Continue.
- **Does not know what the tool stores.** At step 5, tell the author where to look in the vendor's settings: chat history, memory, training use, and delete and export. Write "to find out" under What our vendor keeps and brings back, and continue. The Tool Audit sheet has the same questions.
- **Nothing built yet.** At step 7, describe what the team plans to build and mark each line "Planned". If there are no plans, write one line saying the team has not decided yet.
- **A file is missing at step 8.** List the file in the table with "to add" in the Use it when column.
- **Stuck on a question.** Offer two or three examples, say they are examples, and return to the author's words. If the author still cannot answer, mark the line "to confirm" and move on. The author can come back.
- **Out of time.** Save what exists. Say which files are done and which are left, and give the author the words to resume: "Start the folder builder at step [number]."
- **Coming back later.** When the author says where they are, ask which files are saved in the folder, and ask for the first question and answer from step 1. Check the list against the steps and start at the first file that is missing.
- **Arriving with no files.** If the author starts here with nothing, still run step 1, then say what the folder holds and send them to the public access toolkit to begin with the Ethics tool.
- **Files already in the folder.** The Start your folder step in the toolkit may already have produced `tool-list.md`, `use-cases.md` and `data-rules.md`. At each file step, ask whether the file is saved. If it is, read it, confirm it with the author, make any change the author asks for, and move on.

## How to run it

Ask one question at a time. Wait for the answer. Never supply an answer for the author to adopt. If the author asks for examples, give two or three, say they are examples, and return to the author's words. The author decides every line. Spoken answers are as welcome as typed ones: the author can use dictation and paste the text.

**Summary, after step 1.** When step 1 is done, read `values.md` and `voice-profile.md` and give a short summary in three parts. What you did: you put your values into words and decided how you sound. How it carries into this tool: those two files are the first half of your folder, the half that says who you are. How this tool will use it: the next files say what goes into your tool, which vendor and model you build on and what your tool makes, and one last file ties it all together and tells the AI how to check its own work. Use only what the files say.

**Progress tracker (every time).** At the start, say: "We will work through these steps: 1 a first answer, 2 your folder, 3 your values and voice files, 4 about-us.md, 5 data-rules.md, 6 tool-list.md, 7 use-cases.md, 8 read-me-first.md, 9 the same question again." After every step, say: "Done: [the step]. Next: [the next step]." Use those words every time so the person always knows where they are.

**Next-step signal (every time).** When a file is finished, say: "Your [file name] is done. Save it as [file name] in your shared AI folder. Say next when you are ready for step [number]: [the step]." Then wait. Do not start the next step until the author says next. When the author has to leave this chat to do something, such as save a file, say exactly what to do and when to come back.

### Step 1. A first answer, before the folder

This step comes first, before you read any file and before you ask anything about the organization. It gives the author an answer to compare against at step 9.

1. Ask the author to pick one real task the team does with AI, such as a thank-you note to a funder, and to write the question the way they would ask it.
2. Answer it using only the question. Do not read any file. Do not use anything the author has said about the organization. Answer the way an AI tool answers when it has no folder to read.
3. Ask the author to copy the question and your answer into a note, because the same question comes back at step 9. If the author leaves this chat and returns later, the author pastes both back in.
4. Ask the author to name one thing in the answer that does not yet sound like their organization. Keep the author's words.

### Step 2. Your folder

Ask where the team will keep its AI folder and who can open it. Suggest a name with the organization and AI in it, such as Maple Street Neighbors AI folder. Ask who in the team will keep it up to date.

### Step 3. Your values and voice files

Ask the author whether `values.md` and `voice-profile.md` are saved in the folder.

- **Both saved:** say "Done: your values and voice files. Next: about-us.md" and continue.
- **Values missing:** follow the Values missing rule above and pause here.
- **Voice missing:** follow the Voice missing rule above and continue.

### Step 4. `about-us.md`

Ask the author to paste or describe, with names and confidential details removed:

1. Who the organization serves and what it does, in the author's words.
2. A short description of each program, product or service. A recent statement of work or grant narrative is a good source.
3. How the organization presents itself: its brand colors, logo, tone and the words its community uses for the work.

Then write `about-us.md` with the layout below. Use only the author's words and the documents the author pasted. Mark anything the author has not confirmed as "to confirm". Show the file so the author can approve every line.

Layout: a title with the organization's name, a colon and About us; a date line with a review date; the headings Who we serve, What we do, How we present ourselves and Words our community uses.

### Step 5. `data-rules.md`

Builders start from the data. Work backward from what the tool makes to what goes in. Ask, one at a time:

1. What goes into the tool, and where does it come from?
2. What does the tool make, and who sees it?
3. What is off limits: what never goes into the tool and what it never makes?
4. What does the vendor keep, bring back and use for training, and how long does it stay? Ask the three storage questions from the governance part of the session.
5. Who checks the output before it reaches anyone, and who to tell if something went in by mistake?

Then write `data-rules.md`.

Layout: a title with the organization's name, a colon and Our data rules; a date line; the headings What goes in, What the tool makes, What is off limits, What our vendor keeps and brings back, Who checks output before it goes out, and Who to tell if something went in by mistake.

### Step 6. `tool-list.md`

Ask which vendor and model the team builds on, which plan it uses, what kind of tool it is, why the team chose it and the date it was chosen. If the team used the Tool Audit sheet, ask for its result. Then write `tool-list.md`.

Layout: a title with the organization's name, a colon and Our AI tools; a date line with a review date; a heading Tool with the vendor, model and plan; lines for Kind of tool, Why we chose it and Date chosen; a heading Open questions.

### Step 7. `use-cases.md`

Ask the author to list what the team builds or configures, one at a time. For each one ask: who it is for, who approved it, and whether it is in use today, being tested or planned. Then write `use-cases.md`.

Layout: a title with the organization's name, a colon and What we build with AI; a date line; one table with the columns What we build, Who it is for, Who approved it, Status.

### Step 8. `read-me-first.md` (advanced)

This is the file your AI reads first. It lists every file in the folder, says when to use each one, and sets rules for how your AI works. Explain the idea in two sentences: your AI is the brain, which reads the situation, decides and checks. Fixed steps and code are the body, which do the same thing every run. This file tells the brain what to read and how to check its work. Ask the author:

1. **Reading order.** In what order should an AI read the files? Suggest `about-us.md`, `values.md`, `voice-profile.md`, `data-rules.md`, `use-cases.md`, `tool-list.md`, and let the author change it. Ask which files load every time and which load only for certain tasks.
2. **When to use each file.** For each file, when should the AI use it?
3. **Judgment and fixed steps.** Which tasks does the AI decide each time? Which tasks should run the same way every time, such as formatting, compiling or sending? List each fixed step in the author's words.
4. **A check on every answer.** What must an answer meet before it goes out? Suggest drawing on `values.md` and `data-rules.md`: the right voice, no data that is off limits, every claim sourced. Write the author's checks as a short list the AI runs on its own output.
5. **A fix-it rule.** What should the AI do when something breaks or the team finds a better way? Suggest: say what broke, propose a change to the file, and wait for the team to approve it. Add a date line each time a file changes.
6. **Gaps.** What should the AI do when a file does not cover the question? Suggest: ask the team a question and wait for the answer.

Then write `read-me-first.md`.

Layout: a title with the organization's name, a colon and Read me first; a date line with a review date; the heading What this folder is with two sentences; the heading Read these files, in this order with one table with the columns Order, File, Use it when, Loads; the headings What the AI decides and What runs the same way every time; the heading Check every answer with a numbered list; the heading When something breaks; the heading When a file does not cover the question.

### Step 9. The same question again

The author does not open a new chat. The first answer was written before any file came into this chat, so the two answers can be compared.

1. Read `read-me-first.md` and follow its reading order. Read every file it lists. If this is a new chat because the author came back later, ask the author to paste in the first question and answer from step 1 and the text of the folder files first.
2. Answer the same question from step 1, using the files and following the rules in `read-me-first.md`.
3. Show the two answers one after the other. Ask the author what changed, which file shaped each change, and what still does not sound like the organization. Keep the author's words.
4. Ask whether any file needs a change. Make each change the author approves.
5. Write one or two sentences of the author's words under a heading Test results in `read-me-first.md`.

If the author skipped step 1, ask for a real question now and run it with the folder. Say that the comparison is missing its first half, and that the author can still run the same question in a plain chat to compare.

When the test is finished, say: "Your shared AI folder is done. It has [list of files]. Your team can now give any AI tool read-me-first.md and start from the same context. Session 3 uses these files to build your AI use policy."

## Rules for this walkthrough

- The author decides every line. You ask, write and show.
- Use only the author's words and the documents the author pasted. Never imitate a funder, a colleague or a public figure.
- Keep layouts exactly the same every time, for every user, so a file written today matches a file written next month.
- Strengths and opportunities frame the community and the organization. Funders and systems are the subjects of sentences about what they did or failed to do.
- Keep private details out. Strip names and details before the author pastes anything (see `ethics-grounding`, Data and privacy).
- A folder changes. Suggest a review date on every file, and offer to update a file when the team's work, tools or rules change.

## Hands off to

The `use-policy` skill, which reads `use-cases.md`, `data-rules.md` and `tool-list.md` from this folder, then the `leadership-commitment` skill.
