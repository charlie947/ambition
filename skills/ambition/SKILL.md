---
name: ambition
description: Turn a plain ask into a more ambitious one, then run it. Use when the user says "ambition", "be more ambitious", "push this harder", "aim higher", "Claude is being lazy", "go deeper on this", "what's the goal beyond this", or wants more than the obvious output from a task.
---

# Ambition

A plain ask gets a plain answer. This skill finds the bigger ask inside it, does the whole of it, and hands back something finished the user can act on today.

The frame comes from Felix Rieseberg's post (felixrieseberg.com, 13/10/2026). Speed needs no help, so it is left out.

## 1. Find the ask

Use the task in the message. If there is none, use the last task in the chat. A small mechanical job (a typo, a rename, a date) stays small: say so in one line and do it.

## 2. Pick the direction

Name one lead direction, and a second only if it adds something real.

**Anything people look at or read (a page, a graphic, a video, a deck, copy) leads with Depth, and Range second. Never lead with Altitude on creative work.** Altitude aims past the thing itself, so the thing gets worse. Measured 06/11/2026: a landing page and a motion graphic led by Altitude aimed at sign-ups and looked worse than plain Claude.

| Direction | Use it when | The question |
|---|---|---|
| **Altitude** | There is a real outcome behind the task. A meeting or decision will follow it, or the same job keeps coming back. Weak on creative work | What should happen after this is delivered? What is the goal behind the goal? |
| **Depth** | This one thing has to be excellent | What would the best person in this field do that the ask leaves out? |
| **Range** | The work is creative, or the obvious approach is stale | Which other fields have already solved part of this? |

## 3. Write the bigger ask

**Altitude.** Go up one step at a time and stop at the highest step that is useful.
1. Explain: what changed, why and what to do about it.
2. Decide: the most urgent decisions, with the case for and against each.
3. Replace: a better way to get the result the task exists for, tested against the user's own history and run beside the current way.

Say what access Claude needs to work without the user: the data, the logs, the tools, a way to check its own fix.

**Depth.** The ask must state all of these.
1. What a top professional would do here that was not asked for.
2. The rawest material they would start from, not a digest of it.
3. The real methods and tools they would use. New vocabulary with the old method does not count.
4. A target well beyond the obvious one, treated as reachable. Keep going when it first looks impossible.
5. One belief to test against the raw data, and one new finding to look for.

**Range.** Rewrite the nouns as verbs, because the verbs show which fields apply. A website is not a website. It is getting a stranger on their phone to pick you. List the fields a dream team would need, including someone paid to find the flaw. Borrow what each field does, never how it sounds. Writing in a character's voice changes the transcript and not the result.

**Every version names an outside judge.** A test, a tool, real data, results on data it has not seen, or a fresh chat that never saw the work. Claude judging its own work is not a judge.

## 3b. Creative work: go all out

Anything people look at (a page, a graphic, a video, a deck) gets this on top of Depth. A one-line creative ask is the most underspecified ask there is, so plain Claude ships a competent template. The skill exists to ship the thing a top studio would.

1. **Concepts before pixels.** Write three genuinely different ideas, not three styles of one idea. An idea is a sentence about what the viewer feels or understands ("marketing just got rewired, here is the briefing that keeps up"). Pick the one a jury would remember, say why in one line.
2. **Name the bar.** Name the best real example in this category and the two or three craft moves that make it great (type scale, rhythm, one surprising interaction, a story with beats). Build to that bar, not to "looks fine".
3. **Build more than was asked.** A landing page is the whole page: hero, proof, what you get, a real sample, objections, sign-up twice, footer, and it works on a phone. A motion graphic is a storyboard first: beats with timings, kinetic type, eased motion, a payoff frame. Write the real copy, never lorem ipsum or "Your headline here".
4. **Use the brief's constraints as fuel.** If the user gives colours or fonts, keep them exactly and make them look expensive: contrast, whitespace, one accent used sparingly.
5. **Look at it, then fix it. At least two rounds.** If you can run code, render it and look: screenshot the page at desktop and phone width, or capture frames across the timeline, with any headless browser you have (Playwright, Puppeteer or headless Chrome, wrapped in a timeout). Each round, name the three weakest things against the bar and fix them. If you cannot render (for example in a chat app with no code tools), do the same review by reading the code line by line against the bar, say "not rendered" in your report, and ask the user to open the preview and name the weakest part.
6. **The template test.** Before you hand it back, ask: could this be mistaken for a template with the name swapped in? If yes, it is not done.

## 4. Run it, all the way

Print the bigger ask in one code block before your first tool call, every time, including one-shot and headless runs. Then do the work. Stop at the plan only if the user says "rewrite only". If a skill owns the job, open that skill too and let its rules stand.

**Missing data never stops the run.** Measured 06/11/2026: asked to grow a newsletter with no data in the folder, the skill stopped at the plan and listed what to send. That is a smaller answer than plain Claude gives. Instead:
1. Pick the most likely situation, say it in one line ("I've assumed a B2B newsletter of about 2,000 readers"), and build for it.
2. Use what you can reach: public pages, the web, the files in front of you.
3. Ask for the missing data at the END, as the thing that would make the next version sharper.

**Hand back the finished thing, not advice about it.** "Help me ask for a pay rise" gets the email, the one-page case and the meeting script, written. "Grow my newsletter" gets the plan with dates, the first experiment, and the copy for it. Include at least three moves a top professional would make that the ask left out.

**End with the first thing to do today, ready to paste or send.** Measured 06/11/2026, blind judge, "which would a busy person actually use tomorrow?": the Depth answer alone lost to plain Claude, 6/10 against 8/10 ("it gives you homework before it gives you anything"). The same Depth answer plus a ready-to-send first step won, 8/10 against 6/10.

- If a run needs many agents or long sessions, try the smallest slice first and give the measured cost before going further.
- Ask first before spending money, messaging anyone, publishing, deleting or changing live data.

## 5. Report

Lead with the finished thing. Then give what the judge found, in numbers where there are numbers, in a few lines at the end. The work is the answer, the checks are the footnote.

- A missed target is reported as missed, with the real number. A hard goal never makes a claim true.
- Run the judge yourself whenever you have the tools: open the page, screenshot it, capture the frames, run the test. Write NOT RUN only when you cannot, and name the access that would let you.
- A judge that did not run is written NOT RUN.
- Name anything the skill could not reach, and the access that would open it.
