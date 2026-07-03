<h1 align="center">Tanzim Hossain Romel</h1>

<p align="center">
I ship upstream fixes to .NET, TypeScript, and Apple/container, build benchmark and agent tooling on the side, and write about software security.
</p>

<p align="center">
  <a href="https://tanzimhromel.com">Portfolio</a> |
  <a href="https://github.com/thromel?tab=repositories">Projects</a> |
  <a href="https://github.com/pulls?q=author%3Athromel+type%3Apr+is%3Apublic">Open Source PRs</a> |
  <a href="https://scholar.google.com/citations?user=zHV4EU8AAAAJ">Google Scholar</a> |
  <a href="https://linkedin.com/in/thromel">LinkedIn</a>
</p>

<p align="center">
  <a href="https://gitfut.com/thromel?country=bd">
    <img src="https://gitfut.com/thromel/opengraph-image" alt="GitFut card for thromel" />
  </a>
</p>

---

## What I work on

Six lanes I'm actively contributing in, June 2026 snapshot:

- **.NET and data systems** — EF Core correctness, migrations, relational behavior.
- **Developer tooling** — RefactoringMiner (MCP/WebDiff, AST-diff), compiler fixes in TypeScript and `typescript-go`.
- **Local infrastructure** — Apple `container` networking, hostname/DNS, Compose compatibility.
- **SRE and agent evaluation** — SREGym benchmark scenarios, context compilation, patch validation tied to tests.
- **Agent runtimes** — schema/tooling fixes in LangChain, DeepAgents, and the OpenAI Python SDK.
- **Research** — software security, LLM agent security, empirical SE (papers below).

[69 public authored PRs](https://github.com/pulls?q=author%3Athromel+type%3Apr+is%3Apublic) — 58 outside my own repos, 44 merged.

## Selected projects

| Project | What it does |
| --- | --- |
| [ChannelDeck](https://github.com/thromel/channeldeck) | Native macOS IPTV player for Xtream-style APIs. Multiview, local recording, saved layouts, M3U export. |
| [ctxhelm](https://github.com/thromel/ctxhelm) and [HelmBench](https://github.com/thromel/helmbench) | Local-first context compiler and MCP context broker, plus benchmark work for AI coding agents. |
| [PatchSmith](https://github.com/thromel/patchsmith) | Coding agent for software-maintenance tasks. Sandboxed patch validation, evidence reports per patch. |
| [1brc-csharp](https://github.com/thromel/1brc-csharp) | .NET 10 take on the One Billion Row Challenge. |
| [Yet-Another-C-Compiler](https://github.com/thromel/Yet-Another-C-Compiler) | C/C++ compiler. |
| [CSE-306 / CSE-314](https://github.com/thromel/CSE306-Computer-Architecture-Sessional) | Coursework: 8-bit MIPS pipeline, ALU, FPU; low-level C++ OS work. |

## Selected upstream contributions

| Project | Lane | Notable PRs |
| --- | --- | --- |
| [dotnet/efcore](https://github.com/dotnet/efcore/pulls?q=author%3Athromel) | EF Core correctness, migrations, relational behavior | [#38493](https://github.com/dotnet/efcore/pull/38493), [#37560](https://github.com/dotnet/efcore/pull/37560), [#37415](https://github.com/dotnet/efcore/pull/37415), [#37380](https://github.com/dotnet/efcore/pull/37380) |
| [SREGym](https://github.com/SREGym/SREGym/pulls?q=author%3Athromel) | Kubernetes/SRE benchmark scenarios | [#828](https://github.com/SREGym/SREGym/pull/828), [#821](https://github.com/SREGym/SREGym/pull/821) |
| [tsantalis/RefactoringMiner](https://github.com/tsantalis/RefactoringMiner/pulls?q=author%3Athromel) | MCP server, WebDiff, AST-diff, perf | 15 PRs incl. [#1063](https://github.com/tsantalis/RefactoringMiner/pull/1063), [#1085](https://github.com/tsantalis/RefactoringMiner/pull/1085), [#1101](https://github.com/tsantalis/RefactoringMiner/pull/1101) |
| [apple/container](https://github.com/apple/container/pulls?q=author%3Athromel), [Container-Compose](https://github.com/Mcrich23/Container-Compose/pulls?q=author%3Athromel) | Apple container networking, DNS, Compose | [apple/container#1810](https://github.com/apple/container/pull/1810), [#1811](https://github.com/apple/container/pull/1811), [#1815](https://github.com/apple/container/pull/1815), [Container-Compose#119](https://github.com/Mcrich23/Container-Compose/pull/119) |
| [microsoft/TypeScript](https://github.com/microsoft/TypeScript/pulls?q=author%3Athromel), [typescript-go](https://github.com/microsoft/typescript-go/pulls?q=author%3Athromel) | Compiler behavior, declaration emit, type-system edge cases | [TypeScript#62836](https://github.com/microsoft/TypeScript/pull/62836), [#62899](https://github.com/microsoft/TypeScript/pull/62899), [#62931](https://github.com/microsoft/TypeScript/pull/62931), [typescript-go#3314](https://github.com/microsoft/typescript-go/pull/3314) |
| [langchain-ai](https://github.com/pulls?q=author%3Athromel+org%3Alangchain-ai+type%3Apr), [openai/openai-python](https://github.com/openai/openai-python/pulls?q=author%3Athromel) | Agent/tool schema, model API behavior, CLI reliability | [langchain#34248](https://github.com/langchain-ai/langchain/pull/34248), [#34201](https://github.com/langchain-ai/langchain/pull/34201), [openai-python#2765](https://github.com/openai/openai-python/pull/2765) |

## Research

Two threads I'm publishing in: AI for software engineering, and software/LLM-agent security.

- **[An Empirical Study on Remote Code Execution in ML Model Hosting Ecosystems](https://arxiv.org/pdf/2601.14163)** — ~45k repositories across five ML model hosting ecosystems. Submitted to TOSEM 2026.
- **The Choice Can Be the Attack: Auditing Aligned Backdoors in LLM Agents** — endpoint black-box audit for detecting triggers that change which valid option an LLM agent picks.

## About

Software Engineer at **IQVIA** (healthcare systems). Incoming M.Sc. in Computing Science at the **University of Alberta**, starting September 2026 — joining [U-A-Goose](https://u-a-goose.github.io).

Reach me if you're working on reproducible benchmarks, reviewable patches, runtime evidence, or LLM agent security.

## Contact

- Portfolio: [tanzimhromel.com](https://tanzimhromel.com)
- Email: [tanzimho@ualberta.ca](mailto:tanzimho@ualberta.ca) or [romel.rcs@gmail.com](mailto:romel.rcs@gmail.com)
