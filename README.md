<p align="center">
  <a href="https://xcrap.cc"><img src=".github/assets/banner.png" alt="XCrap — read X (Twitter) without an API key: public posts, threads, profiles and search as Markdown, JSON, YAML, CSV or HTML" width="100%"></a>
</p>

<p align="center">
  <a href="https://xcrap.cc"><img src="https://img.shields.io/badge/xcrap.cc-open-f62d00?style=for-the-badge&labelColor=141312" alt="xcrap.cc"></a>
  <a href="https://xcrap.cc/docs"><img src="https://img.shields.io/badge/docs-API%20reference-f62d00?style=for-the-badge&labelColor=141312" alt="API reference"></a>
  <img src="https://img.shields.io/badge/API%20key-not%20needed-f62d00?style=for-the-badge&labelColor=141312" alt="No API key">
  <a href="https://www.npmjs.com/package/@xcrapcc/sdk"><img src="https://img.shields.io/npm/v/@xcrapcc/sdk?style=for-the-badge&color=f62d00&labelColor=141312&label=node&logo=npm" alt="Node SDK on npm"></a>
  <a href="https://pypi.org/project/xcrap-sdk/"><img src="https://img.shields.io/pypi/v/xcrap-sdk?style=for-the-badge&color=f62d00&labelColor=141312&label=python&logo=pypi&logoColor=white" alt="Python SDK on PyPI"></a>
  <a href="https://www.npmjs.com/package/@xcrapcc/mcp"><img src="https://img.shields.io/npm/v/@xcrapcc/mcp?style=for-the-badge&color=f62d00&labelColor=141312&label=mcp&logo=npm" alt="MCP server on npm"></a>
</p>

<p align="center">
  <b>Read X (Twitter) without an API key.</b><br>
  Paste any public post, thread or profile and get it back as clean Markdown or JSON.<br>
  <sub>No account · no key · nothing to pay</sub>
</p>

---

## ⚡ Try it

```bash
curl 'https://xcrap.cc/v1/tweet?url=https://x.com/jack/status/20&format=markdown'
```

> [!TIP]
> In the browser, swap <kbd>x.com</kbd> for <kbd>xcrap.cc</kbd> in any post link.

## 🧭 How it works

```mermaid
flowchart LR
    you["🧑 You<br/><sub>browser · curl · SDK · agent</sub>"] --> api(["XCrap API"])
    api --> x["X<br/><sub>public posts</sub>"]
    api --> out["Markdown · JSON · YAML · CSV · HTML"]
    classDef accent fill:#f62d00,stroke:#141312,color:#ffffff
    class api accent
```

## 🧰 Use it your way

| | Way in | Get started |
| --- | --- | --- |
| 🌐 | **In the browser** | Swap `x.com` for `xcrap.cc` in any post link |
| 🔌 | **curl / REST** | [API reference](https://xcrap.cc/docs) · [OpenAPI 3.1](https://xcrap.cc/openapi.json) |
| 🟩 | **Node.js** | `npm install @xcrapcc/sdk` · [xcrap-node](https://github.com/XcrapCC/xcrap-node) |
| 🐍 | **Python** | `pip install xcrap-sdk` · [xcrap-python](https://github.com/XcrapCC/xcrap-python) |
| 🤖 | **AI agents (MCP)** | Hosted: `https://xcrap.cc/mcp` · local: `npx -y @xcrapcc/mcp` · [Xcrap-mcp](https://github.com/XcrapCC/Xcrap-mcp) |
| 📖 | **Docs** | [xcrap-docs](https://github.com/XcrapCC/xcrap-docs) · [llms.txt](https://xcrap.cc/llms.txt) · [skills.md](https://xcrap.cc/skills.md) |

> [!NOTE]
> The SDKs and the MCP server are updated with every API change, so they always match what the API returns.

## 📚 What it reads

| 📄 Posts | 🧵 Threads | 💬 Replies | 👤 Profiles | 📜 Timelines | 🗂️ Account history |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **👥 Followers** | **➡️ Following** | **🔎 Search** | **🔥 Trends** | **🖼️ Media** | **📦 Bulk (50 at once)** |

## 🚫 What it will not do

- **Read anything private:** public accounts only.
- **Keep your data:** posts are cached for five days, media is never stored.
- **Charge you later:** there is no key, so there is nothing to bill.
- **Argue with an opt-out:** ask to be excluded and it happens the same day.

## 🏢 Need more?

The free API has per-IP rate limits. The [Enterprise plan](https://xcrap.cc/enterprise) offers higher limits, dedicated capacity, custom endpoints and formats, priority support, and invoices or agreements — same rules, public accounts only. Write to **[hello@xcrap.cc](mailto:hello@xcrap.cc)**.

---

<p align="center">
  <a href="https://xcrap.cc"><b>xcrap.cc</b></a> · <a href="https://xcrap.cc/docs">Docs</a> · <a href="https://xcrap.cc/donate">Donate</a><br>
  <sub>No ads, no investors. Donations keep the free API running. Not affiliated with X Corp.</sub>
</p>
