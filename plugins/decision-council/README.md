# decision-council

A Claude Code plugin that runs a personal decision council so you don't just get your own opinion handed back to you.

## What it does

1. **Interview** – asks seven questions (decision, context, 12-month outcome, constraints, deadline, current lean, biggest fear) in one message and waits.
2. **Five advisers** answer independently: the Contrarian, the First-Principles Thinker, the Expansionist, the Outsider, and the Executor.
3. **Anonymous peer review** – responses are shuffled into A–E and each adviser ranks the other four.
4. **Chairman's verdict** – a single call, confidence, reasons, biggest risk, where the council split, where you might be fooling yourself, dated next steps, and kill criteria.

## Install

```
/plugin marketplace add datkidlollol-wq/Claude-code
/plugin install decision-council@datkidlollol-plugins
```

For local testing from a clone:

```
claude --plugin-dir ./plugins/decision-council
```

## Use

```
/decision-council:council Should I quit my job to go full-time on my side business?
```

Or just ask Claude to "run the council" on a decision — the skill triggers automatically.
