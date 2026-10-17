## Mordehai Attia

Founder of [Corsen AI](https://corsen.ai) — endpoint security for AI agents and MCP.

- 🌐 Website — https://corsen.ai
- 💼 LinkedIn — https://www.linkedin.com/in/mordehai-attia
- 🏢 Corsen AI — https://www.linkedin.com/company/corsenai
- 📍 Paris

### Security research

Independent research on MCP servers and the open source they build on, reported to the maintainers first.

- **AWS Labs `postgres-mcp-server`** — read-only mode bypass leading to OS command execution, [CVE-2026-87911](https://github.com/awslabs/mcp/security/advisories/GHSA-fph8-pg5w-78fv) (critical, fixed in 1.1.7; credited together with Ryan von Brubeck)
- **`mcp-atlassian`** — project and space filter bypass letting an MCP agent read data outside its scope, [CVE-2026-77251](https://github.com/sooperset/mcp-atlassian/security/advisories/GHSA-w66g-j6c4-hcfc) (fixed in 0.22.0)
- **Google `mcp-toolbox`** — missing OAuth audience check in non-MCP mode, fix under review ([PR #3676](https://github.com/googleapis/mcp-toolbox/pull/3676))
- Upstream bug reports: [Cloudflare Pingora #979](https://github.com/cloudflare/pingora/issues/979) (accepted), [Hugging Face `huggingface_hub` #4749](https://github.com/huggingface/huggingface_hub/issues/4749) (fixed in v1.31.0, credited in the fix)
