# Contributing to neuroplastio

neuroplastio's projects are built by their own agents, so we don't take pull
requests. What helps most is an issue in the project's repository: a bug
you hit, or a story about something you were trying to do. Every issue is
read, and the maintainer decides what comes of it.

- **A bug:** the version, the OS, the terminal, and the steps that show it.
- **A story:** something works, but it's unpleasant to use. Tell us what you
  were trying to do, and where you stalled. See [Stories](#stories) below.

If you've dug in, put what you found in the issue: a log with the private
parts taken out, the code you think is at fault, or a fix as a diff. Anything
you post there is offered under the project's license (Apache-2.0). We read a
snippet and write the fix ourselves; we never apply it or run it as posted. If
your analysis shapes the fix, the commit that lands it credits you, and if
your snippet is used close to as you posted it, the commit names you as a
co-author.

Be civil. We lock or delete what isn't.

Security problems don't go in an issue: see [SECURITY.md](SECURITY.md).

To build a project yourself, see its README and `AGENTS.md`.

## Stories

The way to argue for a change in how a tool feels is to write a story: not a
description of the change, but of the situation that made you want it.

An opinion ("the logs view should have X") can only be agreed or disagreed
with. A story ("here's what I was trying to do, and here's where I stalled")
can be walked by somebody else, and either it stalls them too or it doesn't.
That's the difference between a preference and a finding, and with no user
research team and no analytics, it's the only way we have to tell them apart.

A story has three parts, and the story form asks for each:
- **The situation,** in the second person: why is this person at their
  terminal, and what's going on?
- **The goal:** what they're trying to achieve, never how.
- **Where it stalled:** what you reached for that wasn't there, where you
  stopped to think, and how it ended.

**A story never names a key.** "Press `L` to open the logs" measures whether
someone can follow instructions. "Find out what that pod is printing"
measures whether the tool is discoverable, which is the question. The keys a
walker reaches for are the data, so a story that supplies them destroys its
own measurement. Naming a feature ("use the palette to…") is the same
mistake. Describe the goal and stop.

Some projects keep their stories in a `stories/` folder, with a fixture to
walk them against and a way to record the keys you press. A walk with that
record is evidence rather than an anecdote: a key that did nothing shows
where you reached for something that isn't there. Read a record before you
attach it, since it holds everything you typed.

A bug, a crash or wrong output doesn't need a story: open a bug with the
steps. Stories are for when nothing is broken and the thing is still
unpleasant to use.
