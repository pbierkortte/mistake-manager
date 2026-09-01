# Mistake Manager

> [!NOTE]
> ⭐ Don't forget to star this repo. Starring it costs nothing and it will help you remember, or you could just keep making the same mistake. Your call. 😄

## Concept

This skill repurposes your agent's auto-memory to remember mistakes, so you only correct them once.

A cuotiben 错题本 is a notebook for recording wrong answers and reviewing them so they are not made again. This is that notebook, kept in the memory your agent already has.

## Purpose

Corrections do not survive the session. Mistake Manager turns each one into a rule that arrives before the next chance to break it.

## Usage

### Install

```shell
npx openskills install pbierkortte/mistake-manager
```

### Update

```shell
npx openskills update
```

### Invoke

Correcting the agent is usually enough to trigger it.

Slash command:

```shell
/mistake-manager
```

Or ask naturally:

```text
write that correction down as a rule
```

### List

```shell
/skills
```

## Outcome

Each rule is written as part of the fix, before the session that earned it ends, and it reaches the agent at the start of the work unasked. A miss is matched to the rule that would have stopped it rather than the one it resembles, so it raises the count on a rule already kept instead of filing a near duplicate. What grows is a list that reads as rules rather than failures.

## Legal

[LICENSE](LICENSE)
