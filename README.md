<p align="center">
  <img src="./assets/alpineflow.svg" width="100%" alt="Animated alpine landscape"/>
</p>

<h1 align="center">Stalin S</h1>

<p align="center">
  <b>Security Researcher &nbsp;·&nbsp; AI Engineer &nbsp;·&nbsp; OWASP contributor</b><br/>
  I find vulnerabilities in web, API and AI systems, report them responsibly, and build the tooling to do it faster.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/stalin-s-a310882a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@stali.n"><img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium"/></a>
  <img src="https://img.shields.io/badge/HackerOne-active-494649?style=flat-square&logo=hackerone&logoColor=white" alt="HackerOne"/>
  <img src="https://img.shields.io/badge/Bugcrowd-active-F26822?style=flat-square&logo=bugcrowd&logoColor=white" alt="Bugcrowd"/>
  <a href="https://github.com/0x5t4l1n?tab=repositories"><img src="https://img.shields.io/badge/Public_repos-190%2B-1f6feb?style=flat-square&logo=github" alt="Repositories"/></a>
</p>

---

## Focus

| Area | What I work on |
|------|----------------|
| **Application security** | Web and API testing: authorization flaws, injection, path traversal, SSRF, business-logic abuse |
| **AI / LLM security** | Prompt injection, agent and MCP tool abuse, RAG and retrieval risks |
| **Vulnerability research** | Source-code audits, verified proofs of concept, coordinated disclosure |
| **Tooling** | Go and Python tools, agent workflows, attack-surface mapping |

## Published vulnerabilities

Each entry has its own repository with the advisory details, affected versions and proof of concept.

| ID | Product | Weakness | Reference |
|----|---------|----------|-----------|
| [CVE-2026-9506](https://github.com/0x5t4l1n/CVE-2026-9506) | Webkul Bagisto | Path traversal, unauthenticated arbitrary file read (CWE-22) | CERT-In CIVN-2026-0292 |
| [CVE-2026-59924](https://github.com/0x5t4l1n/CVE-2026-59924) | Mistune | Include-directive path traversal, arbitrary file read (CWE-22) | GHSA-r4rv-85jg-w4mf |
| [CVE-2026-42290](https://github.com/0x5t4l1n/CVE-2026-42290) | protobuf.js (`pbts`) | Command injection via unsanitised file paths (CWE-78) | GHSA-f84p-cvgm-xgjj |
| [CVE-2026-117425](https://github.com/0x5t4l1n/CVE-2026-117425) | MkDocs `serve` | Windows path traversal in live-reload server (CWE-22) | GHSA-88gf-v88m-p95v |
| [CVE-2026-29905](https://github.com/0x5t4l1n/CVE-2026-29905) | Kirby CMS | Persistent DoS via malformed image upload (CWE-20) | GHSA-cw7v-45wm-mcf2 |
| [CVE-2026-55062](https://github.com/0x5t4l1n/CVE-2026-55062) | uniget CLI | Path traversal via hook filename (CWE-22) | GHSA-m6jg-wr9m-cg2f |
| [CVE-2026-55061](https://github.com/0x5t4l1n/CVE-2026-55061) | uniget CLI | Argument injection via `EDITOR` (CWE-88) | GHSA-qmcq-xw74-w667 |
| [CVE-2026-45152](https://github.com/0x5t4l1n/CVE-2026-45152) | uniget | Command injection via unsafe check execution (CWE-78) | GHSA-qqq4-5773-pmw5 |
| [CVE-2026-19412](https://github.com/0x5t4l1n/CVE-2026-19412) | CP Plus CP-XR-DE21-S | Hardcoded HTTP Digest credentials (CWE-798) | CERT-In CIVN-2026-0428 |
| [CVE-2026-41039](https://github.com/0x5t4l1n/CVE-2026-41039) | Quantum Networks router | Information disclosure via exposed API endpoints (CWE-200) | CERT-In CIVN-2026-0200 |
| [CVE-2026-41037](https://github.com/0x5t4l1n/CVE-2026-41037) | Quantum Networks router | Missing rate limiting, admin login brute force (CWE-307) | CERT-In CIVN-2026-0200 |
| [CVE-2026-30081](https://github.com/0x5t4l1n/CVE-2026-30081) | Quantum Networks QN-I-470 | Cleartext credential transmission (CWE-319) | CVE reserved |

## Projects

| Project | Description |
|---------|-------------|
| [**CVE**](https://github.com/0x5t4l1n/CVE) | Index of my vulnerability research and disclosures |
| [**Attackgraph**](https://github.com/0x5t4l1n/Attackgraph) | Open-source application-security platform that maps web apps, analyses attack paths and guides evidence-based testing |
| [**alpineflow**](https://github.com/0x5t4l1n/alpineflow) | Go generator for the animated landscape above; also available as the [GitHub Action](https://github.com/0x5t4l1n/alpineflow-action) |
| [**evergreen**](https://github.com/0x5t4l1n/evergreen) | A procedural, living forest in Go, WebAssembly and WebGL2 ([live demo](https://0x5t4l1n.github.io/evergreen/)) |
| [**mkdocs-fix**](https://github.com/0x5t4l1n/mkdocs-fix) | Path-traversal fix for the MkDocs live-reload server |

## Open source contributions

- **[OWASP Hunting](https://github.com/OWASP/OWASP-Hunting)**: curated payloads for ethical security testing and bug bounty. I contribute to the payload library and website ([merged PR #140](https://github.com/OWASP/OWASP-Hunting/pull/140)).
- **OpenTelemetry Collector Contrib**, **Grafana** and **new-api**: bug fixes and improvements.

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust"/>
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Fedora-51A2DA?style=flat-square&logo=fedora&logoColor=white" alt="Fedora"/>
</p>

## GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=0x5t4l1n&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0x5t4l1n&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

---

<p align="center">
  <sub>Disclosures are coordinated with vendors. Reach me on <a href="https://www.linkedin.com/in/stalin-s-a310882a0/">LinkedIn</a>.</sub>
</p>
