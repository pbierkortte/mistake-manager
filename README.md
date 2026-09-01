# Mistake Manager

> [!NOTE]
> ⭐ Don't forget to star this repo. Starring it costs nothing and it will help you remember, or you could just keep making the same mistake. Your call. 😄

## Concept

A cuotiben 错题本 is a notebook for recording wrong answers and reviewing them so they are not made again. Mistake Manager is that notebook, kept by your coding agent.

## Purpose

Corrections do not survive the session. Mistake Manager turns each correction into a rule that arrives before the next chance to break it.

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

Slash command:

```shell
/mistake-manager
```

Or just ask naturally:

```shell
write that correction down as a rule
```

### List

```shell
/skills
```

## Outcome

The rule is written as part of the fix, before the session that earned it ends, and it reaches the agent at the start of the work unasked. A miss is matched to the rule that would have stopped it rather than the one it resembles, so it raises the count on a rule already kept instead of filing a near duplicate. What grows is a list that reads as rules rather than failures.

## Legal

[LICENSE](LICENSE)
