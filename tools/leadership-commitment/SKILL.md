---
name: leadership-commitment
description: Helps your leaders write their AI leadership commitment from your use policy: who is accountable, how often they report, who can pause a tool and how people are told. Use it after your use policy is settled.
---

# Leadership commitment

## What this does

This skill takes your finished use policy and helps your leaders write the commitment that makes it real. It asks who holds each accountability, how often they report to the governing body, who can pause a tool, and how people are told when AI touches their case.

Your leaders decide every answer. The AI asks, drafts from the answers and flags. Your governing body ratifies. No skill signs for anyone.

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

- Your use policy is settled and you want your leaders to commit to it.
- You are updating the commitment after a change in staff, board or tools.
- A funder asks who is accountable for AI at your organization.

If `use-policy.md` does not exist, go back to the `use-policy` skill first. This skill reads the policy before it asks anything.

## Steps

Copy `leadership-commitment-template.md` from this skill folder to `leadership-commitment.md` in your shared AI folder. Ask one question at a time. Wait for the answer. Write each answer in the leaders' words and show the new lines in the read-back at the end of the step.

Before step 1, give a three-line summary, one short line for each part. What you did: you sorted your uses and drafted `use-policy.md` in your team's words. How it carries into this tool: every rule in the policy needs a named person who answers for it. How this tool will use it: the commitment names who is accountable, how often they report to the governing body and who can pause a tool. Use only what the files say.

**Progress tracker.** Say once at the start, on one line: "Steps: 1 your policy, 2 who is here, 3 three accountabilities, 4 five layers, 5 how often and how you will know, 6 pause and stop, 7 telling people, 8 raising a concern, 9 who signs, 10 a check." After each step, say one line: "Done: [the step]. Next: [the next step]."

**Question line.** Follow the Reply rules: every reply starts with the question. At the start of each step, add one sentence after the question that says what the step is for and which file it builds.

**Read-back (once per step).** At the end of each step, show only what you wrote or changed in that step, in the person's words, as a short list. Ask: "Right so far?" Make every change they ask for before you go on.

1. **Read the policy.** Open `use-policy.md` and `values.md`. Say in two sentences what you understand the policy to promise. Ask the leaders to correct you.
2. **Who is here.** Read who is named in `use-policy.md` and say it back. Ask who is in this conversation, the size of the organization and its legal form (nonprofit, public agency, social enterprise or cooperative). Record the answers.
3. **Three accountabilities.** Ask who holds each, in plain terms:
   - The **strategy owner** is accountable for AI strategy, resources and ethical alignment, and reports to the governing body on a stated rhythm.
   - The **operations owner** runs governance day to day: watching the tools in use, updating the policy, coordinating training and checking vendors.
   - The **independent reviewer** checks that the controls work as written and reports to the governing body outside the management chain.
   One person can hold more than one accountability, with one exception. Whoever administers the AI tools cannot be the person who audits them. Ask the leaders how they will keep that separation at their size. If staff capacity is thin, the independence can come from the governing body, with a named person who will actually look.
4. **Five layers.** Walk through policy, oversight, controls, audit and disclosure. For each, ask who holds it at your size and what they do. Use any name already given in this chat or in the policy, and ask only for the layers that are still empty. Record a named person for each, whatever their job title.
5. **How often, and how you will know.** Ask how often the owners report to the governing body and what the report contains. Ask: "How will you know it is working?" Tie the rhythm to the review date in `use-policy.md`.
6. **Pause and stop.** Ask who can pause or stop an AI use, which triggers call for it, and what it takes to turn a tool back on. Include the policy's community harm red flag among the triggers when the leaders agree.
7. **Telling people.** Ask how the organization tells a person when an AI system materially touches their case. Ask whom else it tells, such as funders, the board, residents or members. Write "ask counsel" in `flags.md` for any legal duty.
8. **Raising a concern.** If `use-policy.md` already answers this, show that section with its source and ask only whether it still holds. Otherwise ask how people inside and around the organization report a problem without fear of retaliation, and who receives the report.
9. **Who signs.** List the signers the leaders name and leave the signature and date lines blank.
10. **Check it.** Run the framing pass and co-production check from `ethics-grounding` on the draft. Ask who in the community should hear about the commitment, and how.

When the leaders say it is settled, add the date of this session and the review date from `use-policy.md`. Mark it **Draft: not yet ratified**. Then say: "Save leadership-commitment.md in your shared AI folder." Copy `leadership-commitment-template.md` and match `leadership-commitment-example.md` exactly: the same headings in the same order every time, for every user.

## Rules

- The leaders write the commitment. You ask, draft and flag.
- Do not state what the law requires. Write "ask counsel" in `flags.md`.
- Never fill in a signature, a date of signing or a name the leaders did not give.
- A commitment that names no person, no rhythm and no pause authority stays a draft.

## Hands off to

- `governance-process` for the next stage, which is your governing body's ratification.
- `use-policy` when writing the commitment shows that the policy needs a change.
- `ethics-grounding` at any stop point.
