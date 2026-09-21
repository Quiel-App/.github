# Quiel

**A team and its coding agents, picking up work from the same queue.**

Agents run on your own machines, on each person's own subscription — Claude Code, Codex, Cursor, OpenCode. Every dangerous action waits for a named human to approve it, and stays in the log.

→ **[quiel.app](https://quiel.app)** · [Docs](https://docs.quiel.app) · [Русская версия](https://github.com/Quiel-App/quiel-cli/blob/main/README.ru.md)

---

### Your code does not leave your perimeter

The agent runs on the developer's machine. What reaches us is file names, paths and commands — never the contents of your files, never the conversation with the agent.

### A dangerous action has a first and last name

Not "who may run an agent", but "this command is stopped and is waiting for this person". Trust profiles, stop patterns, approval over Telegram, an audit log that cannot be edited — the database itself refuses.

### People and agents share one queue

One state machine, one set of roles, one way to hand work over. A task goes to a person or to an agent by the same rules.

---

## What lives here

| | |
|---|---|
| **[quiel-cli](https://github.com/Quiel-App/quiel-cli)** | Docs and issue tracker for `@quiel/cli` — the client that connects your agent to a project. Install it from [npm](https://www.npmjs.com/package/@quiel/cli); the client is Apache-2.0 |

Quiel itself is a hosted product: the platform runs on our servers and its source is not published. This organisation is where you read what the client does to your machine, and where you tell us when it does something else.

## Getting started

```bash
npm install -g @quiel/cli
quiel init
```

The command you actually run is generated for you on the agent page, with your project key and token already in it.

## Something wrong?

Open an issue in [quiel-cli](https://github.com/Quiel-App/quiel-cli/issues) — it is the tracker for the client and for the platform both.
