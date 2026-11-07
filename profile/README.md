# neuroplastio

We're working to widen the bandwidth between people and machines.

We build the tools we use every day. Each project starts with a "what if"
question, and we work on what we need most, with the time we have. AI agents
do much of the building: they make it cheap to try an idea, and cheap to drop
it. So some parts of a project are polished and others are still rough, until
we come back to them.

## What we build

**[hotty](https://github.com/neuroplastio/hotty)** — HTML over the TTY: what
if terminals could speak HTML? A spec, a terminal that speaks it, and SDKs
for building with it. Live demo at [hotty.neuroplast.io](https://hotty.neuroplast.io).

- [hottyterm](https://github.com/neuroplastio/hottyterm): a terminal with
  hotty built in, a soft fork of Ghostty (not affiliated with Ghostty)
- [hotty-blitz](https://github.com/neuroplastio/hotty-blitz): the renderer
  terminals link, and `hotty run` for any terminal with kitty graphics
- [xterm-addon-hotty](https://github.com/neuroplastio/xterm-addon-hotty):
  hotty in xterm.js
- SDKs: [Go](https://github.com/neuroplastio/hotty-go),
  [Rust](https://github.com/neuroplastio/hotty-rs),
  [TypeScript](https://github.com/neuroplastio/hotty-ts),
  [Lua](https://github.com/neuroplastio/hotty-lua)
- [hotty-surf](https://github.com/neuroplastio/hotty-surf): a framework for
  hotty apps

**plx**: what if a terminal multiplexer let us try new UI and new workflows
as fast as we think of them? It's where hotty gets used every day.

**[kubecom](https://github.com/neuroplastio/kubecom)**: Kubernetes in your
terminal, with nothing installed in the cluster.

**Libraries** we needed along the way, built to be small, fast and pluggable:
[myelin](https://github.com/neuroplastio/myelin) (keymaps and which-key
menus for Go), [cel-lite](https://github.com/neuroplastio/cel-lite) (CEL for
TinyGo and WebAssembly) and [engram](https://github.com/neuroplastio/engram)
(release channels as a signed, append-only journal).

## Get in touch

Found a bug, or stuck on something? Open an issue in the project; see
[how we take contributions](https://github.com/neuroplastio/.github/blob/main/CONTRIBUTING.md).
For anything else, [toly@neuroplast.io](mailto:toly@neuroplast.io).

More at [neuroplast.io](https://neuroplast.io).
