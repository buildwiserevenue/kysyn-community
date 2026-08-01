# kysyn-community
🌌 Official community hub for KYSYN. Roadmap, bug reports, and feedback for the Neural Backbone for Local Code Intelligence. Powered by the Ouroboros Protocol.

<p align="center">
  <img src="assets/kysyn-logo-dark.png#gh-dark-mode-only" width="180" alt="KYSYN Logo">
  <img src="assets/kysyn-logo-light.svg#gh-light-mode-only" width="180" alt="KYSYN Logo">
</p>

<h1 align="center">KYSYN — Powered by the Ouroboros Protocol</h1>
<p align="center"><strong>The Neural Backbone for Local Code Intelligence</strong></p>
<p align="center"><em>Deterministic by design. Verifiable by anyone.</em></p>

<p align="center">
  <a href="https://kysyn.dev"><strong>Official Website</strong></a> |
  <a href="https://github.com/buildwiserevenue/kysyn-community/discussions"><strong>Get Help</strong></a> |
  <a href="https://github.com/users/buildwiserevenue/projects/1"><strong>Roadmap</strong></a> |
  <a href="https://kysyn.dev/#pricing"><strong>Buy License</strong></a>
</p>

---

## 🚀 What is KYSYN?

KYSYN turns your local codebase into a **deterministic map of its real connections** — who calls what, what depends on what, what breaks if you change this — and serves that truth to you and to your AI.

An LLM cannot see your codebase. It sees fragments and **imagines the rest**: which functions call which, whether "refactor complete" is actually true. Imagining connections has a name — *hallucination*. KYSYN removes the guesswork: every connection on the map is real, and every claim can be checked against it.

- **A map, not a guess:** deterministic structure of your project's actual connections — zero fabricated links.
- **Three-state verdict:** code is judged **live / uncertain / dead** — never a blind yes/no that hides the truth.
- **Total privacy:** runs 100% on your machine. Your code never leaves it.

---

## 🖥️ What You Get

Two surfaces, one graph:

1. **The Desktop App** — fly through your codebase like a galaxy: modules as constellations, connections as they actually exist, from architecture overview down to a single function.
2. **The MCP Server** — plug KYSYN into **Cursor, Claude Code, Claude Desktop, Zed**, or any MCP-compatible environment. Your AI answers from the map instead of imagining — and its "done / connected / removed" claims can be verified against reality.

**Coverage:** 20 code languages with the full three-state verdict — plus 25+ config, build and frontend formats (package manifests, CI pipelines, Docker, and more) wired into the same graph, so the map spans the layer most tools ignore.

---

## ⚙️ How It Works

1. **Index.** Point KYSYN at your project. It builds the map locally — every symbol, every real connection, across code *and* the config/build layer that wires it together.
2. **Judge.** Every symbol gets a three-state verdict: **live** (provably reached), **uncertain** (there is evidence, but not proof — resolve it, don't delete it), **dead** (zero signal). Never a blind yes/no: the uncertain bucket is where honest tools admit what a binary verdict would fake.
3. **Navigate & serve.** You explore the map visually in the desktop app; your AI queries the same map over MCP — who calls this, what breaks if I change it, is this really dead — and gets answers backed by the graph, not by imagination. When your agent claims "done / connected / removed", the map is the counter-question it cannot talk its way around.

Nothing is sampled, nothing is guessed: re-index the same code and you get the same map. That's what *deterministic* means here — and why the verdicts are worth trusting.

📚 Full usage documentation: [kysyn.dev/docs](https://kysyn.dev/docs/quickstart/)

---

## 🧬 The Ouroboros Protocol

KYSYN is built and tested **on itself**: the engine indexes its own source code, and its verdicts gate its own development — the ouroboros eating its own tail. Every release ships only after the map of a complex, real codebase (this one) proves correct.

That is also why the claims are verifiable by *you*: the same verdicts KYSYN produces for its own code, it produces for public repositories anyone can index. See the proof on the [website](https://kysyn.dev/#proof).

---

## 📅 Future & Roadmap

KYSYN's future is driven by its community.
- 📍 **Public Roadmap:** [KYSYN Roadmap](https://github.com/users/buildwiserevenue/projects/1)
- 💡 **Suggestions:** Open a "Feature Request" in the Issues tab to propose new capabilities.

---

## 🆘 How to Get Help

Found a bug or need technical support?
1. Check existing **Issues** to see if the problem is already being tracked.
2. Open a **New Issue** providing logs (scrubbed of sensitive data) and steps to reproduce. The app can package a support bundle for you — you review its contents before sharing anything.
3. For license or billing inquiries, please contact `support@kysyn.dev`.

---

## 🤝 Contributing

The KYSYN source code is **proprietary** and is not hosted in this repository. However, we actively encourage participation in this hub:
- Bug reporting and edge-case documentation.
- User experience feedback.
- Proposals for new tool integrations.

---

## ⚖️ Legal

KYSYN is a local-first application committed to user privacy.
- **Privacy:** [kysyn.dev/legal/privacy](https://kysyn.dev/legal/privacy)
- **Terms:** [kysyn.dev/legal/terms](https://kysyn.dev/legal/terms)
- **Cookies:** [kysyn.dev/legal/cookies](https://kysyn.dev/legal/cookies)
- **Refunds:** [kysyn.dev/legal/refund](https://kysyn.dev/legal/refund)

---

## 📜 License

The documentation we write in this repository (this README and the issue and discussion templates) is released under the **MIT License**.

Three things it does **not** cover: the **KYSYN software**, which is proprietary and distributed under the **KYSYN Commercial License**, available for purchase at [kysyn.dev](https://kysyn.dev); the **KYSYN name and logos**, which are trademarks and are not licensed here; and everything **you** write — your issues, discussions and reviews stay yours, and a review is quoted on our site only with your explicit consent and a link back to your original thread.

---

<p align="center">KYSYN is built with ❤️ by a <strong>solo developer</strong> — and that is exactly why trust is never asked for, only verified. No cloud traps, no data leaks. Just pure code intelligence.</p>

---

<p>© 2026 KYSYN. All rights reserved.</p>
