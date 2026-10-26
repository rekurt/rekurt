# Hi, I'm Nikita

I develop financial software and lead large engineering teams. My experience covers banking and lending platforms, financial-service integrations, trading systems, and algorithmic trading. I also work with blockchain, Web3, and cryptocurrencies, alongside AML, financial forensics, data analysis, and back-office process design.

My engineering background extends to ballistics and hardware-oriented software: embedded systems, real-time systems, and hardware–software integration. Alongside hands-on development, I manage people and build the processes that help large development teams deliver complex systems.

Outside my professional work, I build open-source projects as a hobby. This GitHub profile is a space for personal experiments and independent projects, rather than a portfolio of my professional work.

[Explore all projects](https://rekurt.github.io/projects/)

## Selected open-source tools & projects

### [CortexForge](https://github.com/rekurt/cortex-forge) · Multi-tenant Hermes Agent platform

For engineering teams running isolated AI assistants across an organization. Deploy from 1 to 1,000+ isolated [NousResearch Hermes Agent](https://github.com/NousResearch/hermes-agent) containers on Docker Compose with zero API key exposure, real-time SSE streaming token quotas, and an inter-agent SQLite WAL message broker.

[Project website](https://rekurt.github.io/cortex-forge/) · [1,000-User Enterprise guide](https://github.com/rekurt/cortex-forge/blob/master/docs/ENTERPRISE_1000_USERS.md) · [10-second demo](https://github.com/rekurt/cortex-forge#-try-it-in-10-seconds-zero-docker--zero-api-keys-needed)

### [OpenKline](https://github.com/rekurt/openkline) · Candlestick charts

For developers building trading interfaces and market dashboards. Interactive price charts with indicators and drawing tools, powered by a framework-independent TypeScript core with React and Vue wrappers.

[Playground](https://rekurt.github.io/openkline/) · [API reference](https://rekurt.github.io/openkline/api/) · [Install](https://github.com/rekurt/openkline#install)

### [Depth](https://github.com/rekurt/depth) · Order-book visualization

For web applications that need to show market liquidity. A TypeScript canvas chart with cumulative depth, spread metrics, and dark and light themes.

[Interactive demo](https://rekurt.github.io/depth/demo/) · [Quick start](https://github.com/rekurt/depth#quick-start) · [Install](https://github.com/rekurt/depth#install)

### [matching-engine](https://github.com/rekurt/matching-engine) · Spot order matching

A Rust service for matching spot orders with price-time priority and fixed-point arithmetic. Binary protocol v2, WAL recovery, TLS/mTLS and a Go client, with integration examples in four languages. Account balances and settlement belong to the surrounding platform.

[Project website](https://rekurt.github.io/matching-engine/) · [Handbook](https://rekurt.github.io/matching-engine/docs/) · [Quick start](https://rekurt.github.io/matching-engine/docs/quickstart.html)

### [dbdiff](https://github.com/rekurt/dbdiff) · Database schema comparison

For developers reviewing schema changes and checking drift in CI. Compare PostgreSQL, MySQL/MariaDB, and SQLite schemas; generate migration SQL for review, with offline comparisons and structured reports.

[Offline demo](https://github.com/rekurt/dbdiff#try-the-demo) · [CLI guide](https://github.com/rekurt/dbdiff/blob/master/doc/cli.md) · [Install](https://github.com/rekurt/dbdiff#install)

### [GitLab Dump](https://github.com/rekurt/gitlab-downloader) · Repository transfers

For teams moving repositories between GitLab instances. Clone groups and plan transfers through a CLI or desktop app, with previews, reports, and explicit handling of conflicts.

[CLI guide](https://github.com/rekurt/gitlab-downloader#cli) · [Transfer limits](https://github.com/rekurt/gitlab-downloader#direct-transfer-compatibility) · [Install](https://github.com/rekurt/gitlab-downloader#install-from-npm)

### [ymsdk](https://github.com/rekurt/ymsdk) · Yandex Messenger bots in Go

For Go developers building bots and messaging integrations. Typed API clients, configurable retries, polling, and webhooks, with examples for messages, polls, and incoming updates.

[English guide](https://github.com/rekurt/ymsdk/blob/master/README.en.md) · [API reference](https://pkg.go.dev/github.com/rekurt/ymsdk) · [Install](https://github.com/rekurt/ymsdk/blob/master/README.en.md#installation)

### [prt](https://github.com/rekurt/prt) · Network inspection in the terminal

For developers and administrators investigating local connections on macOS and Linux. Find port conflicts, inspect processes, and manage SSH tunnels from a keyboard-driven terminal interface.

[Demo](https://github.com/rekurt/prt#demo) · [Usage](https://github.com/rekurt/prt#command-line-modes) · [Install](https://github.com/rekurt/prt#install-and-run)

<details>
<summary>See project previews</summary>

**OpenKline** — playground with synthetic demo candles.

[![OpenKline playground showing candlesticks, an SMA overlay, and volume bars](https://raw.githubusercontent.com/rekurt/openkline/master/docs/images/playground-candles.png)](https://rekurt.github.io/openkline/)

**Depth** — order-book depth chart.

[![Depth canvas chart showing bid and ask liquidity in a dark theme](https://raw.githubusercontent.com/rekurt/depth/master/docs/assets/pro-dark-terminal.png)](https://rekurt.github.io/depth/demo/)

**dbdiff** — output from the offline schema comparison demo.

[![dbdiff terminal output showing schema changes and CI exit codes](https://raw.githubusercontent.com/rekurt/dbdiff/master/doc/assets/demo.png)](https://github.com/rekurt/dbdiff#try-the-demo)

**prt** — terminal connection inspector.

[![prt terminal interface with connections and process details](https://raw.githubusercontent.com/rekurt/prt/master/docs/prt-demo.png)](https://github.com/rekurt/prt#demo)

</details>

---

Found something useful? Try the demo or installation guide. Bug reports, focused pull requests, and documentation improvements are welcome in each project's repository.
