<h1 align="center">Tanzim Hossain Romel</h1>

<p align="center">
Software engineer and researcher building developer tools, SRE benchmarks, AI-agent infrastructure, and reliable open-source systems.
</p>

<p align="center">
  <a href="https://tanzimhromel.com">Portfolio</a> |
  <a href="https://github.com/thromel?tab=repositories">Projects</a> |
  <a href="https://github.com/pulls?q=author%3Athromel+type%3Apr+is%3Apublic">Open Source PRs</a> |
  <a href="https://scholar.google.com/citations?user=zHV4EU8AAAAJ">Google Scholar</a> |
  <a href="https://linkedin.com/in/thromel">LinkedIn</a>
</p>

---

## Open Source Focus

I use GitHub as a working portfolio: upstream fixes, benchmark harnesses, agent tooling, and small products that ship.

June 2026 snapshot: **69 public authored PRs**, including **58 PRs outside my own repositories** and **44 merged PRs**. Full index: [author:thromel public PRs](https://github.com/pulls?q=author%3Athromel+type%3Apr+is%3Apublic).

Current contribution lanes:

- **.NET and data systems**: EF Core correctness fixes, runtime migration work, relational behavior, and developer-facing diagnostics.
- **Developer tooling**: RefactoringMiner MCP/WebDiff work, AST-diff correctness, compiler/toolchain fixes, and AI-assisted review workflows.
- **Local infrastructure**: Apple `container` networking, hostname/DNS behavior, and Compose compatibility.
- **SREGym and agent evaluation**: Kubernetes/SRE benchmark scenarios, context-compilation tooling, and evidence-focused patch validation.

## Selected Upstream Contributions

| Project | Contribution lane | PRs |
| --- | --- | --- |
| [dotnet/efcore](https://github.com/dotnet/efcore/pulls?q=author%3Athromel) | EF Core correctness, migrations, and relational behavior | [#38493](https://github.com/dotnet/efcore/pull/38493) complex collection original values, [#37560](https://github.com/dotnet/efcore/pull/37560) nullable complex reload, [#37415](https://github.com/dotnet/efcore/pull/37415) runtime migration creation/application, [#37380](https://github.com/dotnet/efcore/pull/37380) `ON DELETE SET DEFAULT` |
| [SREGym/SREGym](https://github.com/SREGym/SREGym/pulls?q=author%3Athromel) | Kubernetes/SRE benchmark problems and failure-mode modeling | [#828](https://github.com/SREGym/SREGym/pull/828) Calico route-reflector label drift, [#821](https://github.com/SREGym/SREGym/pull/821) priority preemption cascade |
| [tsantalis/RefactoringMiner](https://github.com/tsantalis/RefactoringMiner/pulls?q=author%3Athromel) | MCP server support, WebDiff workflows, AST-diff robustness, performance fixes | 15 authored PRs, including [#1063](https://github.com/tsantalis/RefactoringMiner/pull/1063), [#1064](https://github.com/tsantalis/RefactoringMiner/pull/1064), [#1085](https://github.com/tsantalis/RefactoringMiner/pull/1085), [#1087](https://github.com/tsantalis/RefactoringMiner/pull/1087), [#1101](https://github.com/tsantalis/RefactoringMiner/pull/1101) |
| [apple/container](https://github.com/apple/container/pulls?q=author%3Athromel) and [Container-Compose](https://github.com/Mcrich23/Container-Compose/pulls?q=author%3Athromel) | Apple container networking, hostname/DNS behavior, and Compose compatibility | [apple/container#1810](https://github.com/apple/container/pull/1810), [#1811](https://github.com/apple/container/pull/1811), [#1813](https://github.com/apple/container/pull/1813), [#1815](https://github.com/apple/container/pull/1815), [Container-Compose#119](https://github.com/Mcrich23/Container-Compose/pull/119) |
| [microsoft/TypeScript](https://github.com/microsoft/TypeScript/pulls?q=author%3Athromel), [microsoft/typescript-go](https://github.com/microsoft/typescript-go/pulls?q=author%3Athromel) | Compiler behavior, declaration emit, and type-system edge cases | [TypeScript#62836](https://github.com/microsoft/TypeScript/pull/62836), [#62899](https://github.com/microsoft/TypeScript/pull/62899), [#62904](https://github.com/microsoft/TypeScript/pull/62904), [#62931](https://github.com/microsoft/TypeScript/pull/62931), [typescript-go#3314](https://github.com/microsoft/typescript-go/pull/3314) |
| [langchain-ai](https://github.com/pulls?q=author%3Athromel+org%3Alangchain-ai+type%3Apr) and [openai/openai-python](https://github.com/openai/openai-python/pulls?q=author%3Athromel) | Agent/tool schema handling, model API behavior, and CLI reliability | [langchain#34248](https://github.com/langchain-ai/langchain/pull/34248), [#34201](https://github.com/langchain-ai/langchain/pull/34201), [#34376](https://github.com/langchain-ai/langchain/pull/34376), [deepagents#2396](https://github.com/langchain-ai/deepagents/pull/2396), [openai-python#2765](https://github.com/openai/openai-python/pull/2765) |
| [Kaliumhexacyanoferrat/GenHTTP](https://github.com/Kaliumhexacyanoferrat/GenHTTP/pulls?q=author%3Athromel), [gudarzi/SaveHere](https://github.com/gudarzi/SaveHere/pulls?q=author%3Athromel), [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh/pulls?q=author%3Athromel) | Web framework behavior, downloader reliability, and developer tooling quality-of-life fixes | GenHTTP [#770](https://github.com/Kaliumhexacyanoferrat/GenHTTP/pull/770), [#771](https://github.com/Kaliumhexacyanoferrat/GenHTTP/pull/771), [#772](https://github.com/Kaliumhexacyanoferrat/GenHTTP/pull/772), [#773](https://github.com/Kaliumhexacyanoferrat/GenHTTP/pull/773); SaveHere [#69](https://github.com/gudarzi/SaveHere/pull/69), [#71](https://github.com/gudarzi/SaveHere/pull/71), [#72](https://github.com/gudarzi/SaveHere/pull/72), [#73](https://github.com/gudarzi/SaveHere/pull/73); [ohmyzsh#13472](https://github.com/ohmyzsh/ohmyzsh/pull/13472) |

## Selected Projects

| Project | What it is | Why it is here |
| --- | --- | --- |
| [ChannelDeck](https://github.com/thromel/channeldeck) | Native macOS IPTV player for Xtream-style accounts | Public Swift app with releases; latest release adds multiview playback, local recording, saved layouts, and M3U export |
| [ctxhelm](https://github.com/thromel/ctxhelm) and [HelmBench](https://github.com/thromel/helmbench) | Local-first context compiler, MCP context broker, and benchmark work for AI coding agents | Systems/tooling research around context quality, navigation, and agent workflows |
| [patchsmith](https://github.com/thromel/patchsmith) | Research platform for evaluating AI software-maintenance agents with sandboxed patch validation and evidence reports | Evaluation infrastructure for evidence-backed software-maintenance agents |
| [1brc-csharp](https://github.com/thromel/1brc-csharp) | .NET 10 solution for the One Billion Row Challenge | Performance-oriented C#/.NET systems work |
| [Yet-Another-C-Compiler](https://github.com/thromel/Yet-Another-C-Compiler) | C/C++ compiler project | Older systems project showing compiler pipeline work and low-level implementation experience |
| [CSE306 Computer Architecture Sessional](https://github.com/thromel/CSE306-Computer-Architecture-Sessional) | ALU, floating-point adder, and pipelined 8-bit MIPS processor work | Older computer-architecture project with simulator-facing hardware design artifacts |
| [CSE-314 Operating System Sessional](https://github.com/thromel/CSE-314-Operating-System-Sessional) | Operating-systems coursework and systems programming | Older low-level C++/systems project that rounds out the portfolio beyond web/profile work |

## Research

I work at the intersection of software engineering, security, and AI-assisted development.

- **AI for Software Engineering**
- **Software Security**
- **LLM Agent Security**
- **Empirical Software Engineering**

Selected work:

- **[An Empirical Study on Remote Code Execution in ML Model Hosting Ecosystems](https://arxiv.org/pdf/2601.14163)**
  Large-scale study of roughly 45,000 repositories across five ML model hosting ecosystems. Submitted to TOSEM 2026.

- **The Choice Can Be the Attack: Auditing Aligned Backdoors in LLM Agents**
  Endpoint-black-box audit design for detecting hidden triggers that covertly change which valid option an LLM agent chooses.

## About

Software Engineer at **IQVIA** building healthcare systems at scale. Incoming **M.Sc. in Computing Science** student at the **University of Alberta** starting in **September 2026**, joining **[U-A-Goose](https://u-a-goose.github.io)**.

I am most interested in systems where engineering quality is measurable: reproducible benchmarks, reviewable patches, runtime evidence, and security boundaries that hold up under real workflows.

## Contact

- Portfolio: [tanzimhromel.com](https://tanzimhromel.com)
- Email: [tanzimho@ualberta.ca](mailto:tanzimho@ualberta.ca)
- Email: [romel.rcs@gmail.com](mailto:romel.rcs@gmail.com)
