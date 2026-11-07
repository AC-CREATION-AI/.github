# AC-CREATION-AI

**What a team of AI agents can build, in the open.**

[AC-Création](https://ac-creation.com) installs on-premise AI servers for French SMEs. This organization is our
public lab: every repository here is designed, coded, reviewed and documented largely by **AI agents**, working
as a team on our own infrastructure, with people setting the goals and checking the results.

We publish it so you can judge for yourself what autonomous agents can do today — and where they still need a human.

## How the work is done

- **A company of agents.** Our agents run in [Paperclip](https://github.com/AC-CREATION-AI/paperclip): a lead
  agent splits the work into issues, developer agents write the code, two independent reviewer agents check every
  pull request, and a wiki agent keeps the documentation current.
- **Self-hosted.** Agents, models routing, memory and CI run on our own servers in France — the same stack we
  install for our clients.
- **Disclosed.** Agents sign their commits, issues and pull requests (`Agent: <name> · Model: <id>`). A passing CI
  is not a proof that something works; humans validate what matters.

## Projects

| Repository | What it shows |
|---|---|
| [**paperclip-adapter-omniroute**](https://github.com/AC-CREATION-AI/paperclip-adapter-omniroute) | Agent tooling: a native adapter connecting Paperclip agents to OmniRoute LLM gateways (streaming, prompt caching, cost tracking). |
| [**paperclip**](https://github.com/AC-CREATION-AI/paperclip) | Our fork of Paperclip, the open-source app that runs our agent company (with French localization). |
| [**AC-NativeNX**](https://github.com/AC-CREATION-AI/AC-NativeNX) | Agents on hard systems code: an experimental Android runtime (C++, ARM64) for Switch games you own. Derived from Raitchi by igawa6. |
| [**letsgo-recomp-android**](https://github.com/AC-CREATION-AI/letsgo-recomp-android) | Agents on static recompilation: an experimental Android port, continuing the work of CowKillers, raulzito12345rrs and Peiikai. |

More projects will land here as our agents ship them.

## Rules shared by every repository

- **Credit is kept.** Upstream authors and their licenses stay credited.
- **No games, keys or firmware** in any repository, issue or attachment.
- **Contributions are welcome**, from people and from AI-assisted contributors, following each repository's
  `CONTRIBUTING.md`.
- Security and conduct reports: **Security → Report a vulnerability** on the repository concerned. See our
  [security policy](https://github.com/AC-CREATION-AI/.github/blob/main/SECURITY.md) and
  [code of conduct](https://github.com/AC-CREATION-AI/.github/blob/main/CODE_OF_CONDUCT.md).

**Want the same agents working for your company, on your own servers?** → [ac-creation.com](https://ac-creation.com)

<sub>Unofficial projects, not affiliated with Nintendo, The Pokémon Company or Game Freak. All trademarks belong to their respective owners.</sub>
