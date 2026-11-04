# Ambition

A free Claude skill that finds the bigger job inside your ask, then does it.

You describe a task, you give Claude everything it needs, and it still falls short. Usually that's because the ask was small.

Type `/ambition` and one line. It writes a bigger brief with a target and an outside check, shows it to you, then does the work.

```
/ambition Build me a website for my coffee shop.
```

## Install

The skill is free. It runs in Claude Code, which needs a paid Claude plan (Pro or above).

In Claude Code:

```
/plugin marketplace add charlie947/ambition
/plugin install ambition@ambition
```

Or copy `skills/ambition/SKILL.md` to `~/.claude/skills/ambition/SKILL.md`.

## The three principles

They come from [Felix Rieseberg's article](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/). Felix is an engineering manager at Anthropic.

| Principle | The question | Best for |
|---|---|---|
| Altitude | What should happen after this is delivered? | A job with a real outcome behind it |
| Depth | What would the best person in this field do that you left out? | One thing that has to be excellent |
| Range | Which other fields have already solved part of this? | Creative work, or a stale approach |

The skill picks the lead one, and a second only if it adds something real. It also makes Claude name an outside check, because Claude marking its own work isn't a check.

## What to expect

I ran that coffee shop line 3 times on Opus, with tools off. All 3 wrote the bigger brief, then built a page with sample details. All 3 named outside checks, and none could run them with tools off.

So one line gets you a better brief and a template. Give it your real menu, numbers and access, and it has something real to work from. You still have to check what comes back.

Small jobs stay small. A typo or a rename just gets done.

## Credit

This is my skill, built on Felix's article. It isn't from Anthropic.

MIT licence. Made by [Charlie Hills](https://charliehills.substack.com).
