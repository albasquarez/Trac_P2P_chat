# ⚡ PeerPulse Pro — AI-Powered P2P Chat on Trac Network

> A fork of [Trac-Systems/intercom-swap](https://github.com/TracSystems/intercom-swap) that adds a real-time AI assistant (Claude) embedded directly into the Intercom sidechannel UI — making P2P communication smarter and more capable.

---
![aiagent2jpg](https://github.com/user-attachments/assets/d7b80649-c69d-4dd1-b316-4117eb8d403b)
![aiagent](https://github.com/user-attachments/assets/0169f60d-e4d7-472e-a3f2-c30532636ba7)


## 🔑 TRAC ADDRESS

```
trac1na2880rtaa7zqy9dlkl935v27q322pe4ekljewdq7rsusz9c0hqssecn7np
```

---

## 📖 What is PeerPulse Pro?

**PeerPulse Pro** is an agentic Intercom app that merges the **Trac Network P2P sidechannel layer** with a live **AI assistant (Anthropic Claude)**. It runs as a standalone `index.html` UI that peers can open locally — no server required — and interact with both the P2P network and an intelligent AI agent simultaneously.

This fork builds on top of `intercom-swap`'s sidechannel infrastructure and adds:

- 🤖 **Real AI replies** via Anthropic Claude (claude-sonnet) — not scripted bots
- 🔐 **End-to-end encrypted interface** over Trac/Holepunch sidechannels
- 💬 **Persistent conversation context** — the AI remembers your session
- ⚡ **Zero server required** — pure P2P + AI-at-the-edge
- 🎨 **Production-grade cyberpunk UI** — modern dark theme, animated, mobile-ready

---

## 🧠 Why This Matters for Trac Network

The Intercom stack was designed as an **internet of agents** — peers that can coordinate, negotiate, and communicate without central servers. PeerPulse Pro takes this one step further: it gives every peer a **locally-embedded AI agent** that can reason, answer questions, help negotiate, and assist with on-chain decisions — all within the encrypted P2P channel.

This is a real demonstration of the Trac vision: **autonomous agents communicating peer-to-peer**, enhanced by AI intelligence at the edge.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🤖 AI Chat | Real Claude AI responses with full conversation memory |
| 🔐 E2E Encryption UI | Interface styled for encrypted Trac sidechannel usage |
| ⚡ Quick Prompts | One-click starter questions for new users |
| 📱 Responsive Design | Works on desktop and mobile |
| 🌐 No Backend | Single HTML file, runs anywhere |
| 💡 AI Context Awareness | AI is briefed about Trac Network and Intercom |

---

## 🛠 How to Use

### Option 1 — Standalone (no install)
Just open `index.html` in any modern browser. The AI chat works immediately.

### Option 2 — With Trac Intercom (full P2P)
This UI is designed to be paired with the Intercom sidechannel backend:

```bash
# Install Pear runtime
npm i -g pear

# Clone this repo
git clone https://github.com/albasquarez/Trac_P2P_chat
cd Trac_P2P_chat

# Install dependencies
npm install

# Run as Pear app
pear run . --peer-store-name mypeer
```

Then open `index.html` in your browser — the AI assistant becomes your local agent companion.

---

## 🏗 Architecture

```
  Browser (index.html)
       |
       |-- User sends message
       |
       v
  [AI Layer] Anthropic Claude API
       |-- Full conversation history maintained
       |-- Context: Trac Network, P2P, crypto
       |
  [P2P Layer] Trac/Holepunch Sidechannel
       |-- Hyperswarm peer discovery
       |-- Protomux multiplexing
       |-- Optional relay
```

---

## 🔗 Links

- **Upstream intercom**: https://github.com/Trac-Systems/intercom
- **Upstream intercom-swap**: https://github.com/TracSystems/intercom-swap
- **Awesome Intercom list**: https://github.com/Trac-Systems/awesome-intercom
- **Trac Network**: https://www.tracnetwork.org

---

## 📜 License

MIT — same as upstream Intercom. See [LICENSE.md](LICENSE.md)

---

## 🙏 Credits

Built on top of the excellent work by [Trac-Systems](https://github.com/Trac-Systems) and the Holepunch/Hypercore ecosystem.

> *"The internet of agents needs intelligence at the edge — PeerPulse Pro puts an AI directly in your P2P channel."*
