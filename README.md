# The first on-chain AI agent Powered by ElizaOS 🤖

<div align="center">
  <img src="https://pictr.com/images/2025/01/10/x1C06B.jpg" alt="Eliza Banner" width="100%" />
</div>

<div align="center">

 🎯 [Website](https://paintera.xyz/) | 📖 [Documentation](https://elizaos.github.io/eliza/)

</div>

## 🌍 README Translations

[中文说明](./README_CN.md) | [日本語の説明](./README_JA.md) | [한국어 설명](./README_KOR.md) | [Français](./README_FR.md) | [Português](./README_PTBR.md) | [Türkçe](./README_TR.md) | [Русский](./README_RU.md) | [Español](./README_ES.md) | [Italiano](./README_IT.md) | [ไทย](./README_TH.md) | [Deutsch](./README_DE.md) | [Tiếng Việt](./README_VI.md) | [עִברִית](https://github.com/elizaos/Elisa/blob/main/README_HE.md) | [Tagalog](./README_TG.md) | [Polski](./README_PL.md) | [Arabic](./README_AR.md) | [Hungarian](./README_HU.md) | [Srpski](./README_RS.md)

## 🚩 Overview

<div align="center">
  <img src="./docs/static/img/eliza_diagram.jpg" alt="Eliza Diagram" width="100%" />
</div>



# TEE & pAIntera Capital: Secure Trading Infrastructure

Combining AMD SEV-SNP and TPM 2.0 technologies to create an impenetrable fortress for your trading algorithms. pAIntera Capital Trusted Execution Environment ensures complete isolation and protection of your sensitive trading operations.

## Trusted Execution Environment

### Memory Encryption

AMD SEV-SNP provides real-time memory encryption with unique keys per VM, preventing memory snooping and cold boot attacks.

### Secure Boot Chain

Verified boot process ensures system integrity from UEFI to application layer.

### Attestation

Hardware-based remote attestation proves the authenticity of the execution environment.

### Isolated Execution

Complete isolation from host OS and other VMs, protecting sensitive computations.

## Secure Architecture Overview

### Hardware Layer

- AMD SEV-SNP CPU
- TPM 2.0 Module
- Secure Memory

### Security Layer

- Memory Encryption
- Key Management
- Process Isolation

### Application Layer

- Trading Logic
- Risk Management
- Access Control

## Multi-Layer Security Architecture

### Hardware Security

- ✓TPM 2.0 Integration
- ✓AMD SEV-SNP Support
- ✓Memory Encryption
- ✓Secure Page Tables

### Key Management

- ✓Hardware-Sealed Keys
- ✓Secure Key Hierarchy
- ✓Attestation Binding
- ✓Rotation Policies

### Runtime Protection

- ✓Memory Isolation
- ✓Stack Protection
- ✓ASLR Implementation
- ✓Control Flow Integrity

## Technical Implementation

Our secure trading agent leverages hardware-based security features to establish a robust trusted execution environment. The implementation utilizes AMD's SEV-SNP technology for memory encryption and isolation, combined with TPM 2.0 for secure key storage and attestation.

### Key Management

- Hardware-sealed key storage
- Secure key rotation
- Performance optimization

### Runtime Security

- Memory encryption
- Process isolation
- Continuous monitoring

## AI Trading in Secure Environment

### Secure Model Execution

AI models run within TEE, protecting proprietary trading strategies and preventing model extraction attacks.

### Protected Data Pipeline

End-to-end encryption for market data processing and signal generation within secure enclaves.

### Confidential Inference

Model inference performed in encrypted memory, ensuring prediction privacy and strategy confidentiality.

### Secure Model Updates

Authenticated and encrypted model updates with hardware-backed verification.

## Unified Security Architecture

### AI Security

- ✓Model Protection
- ✓Data Privacy
- ✓Secure Training
- ✓Protected Inference

### Trading Performance

- ✓Low Latency
- ✓High Throughput
- ✓Reliable Execution
- ✓Consistent Performance

### TEE Advantages

- ✓Hardware Isolation
- ✓Memory Encryption
- ✓Secure Boot
- ✓Remote Attestation

## Secure Trading Workflow

### 1. Secure Initialization

Hardware-verified boot process and TEE establishment with remote attestation

### 2. Protected Model Loading

Encrypted AI models loaded into secure memory with integrity verification

### 3. Secure Data Processing

Real-time market data processed within encrypted memory space

### 4. Protected Trade Execution

Trade signals generated and executed with hardware-backed signatures

## ✨ Features

- 🛠️ Full-featured Discord, Twitter and Telegram connectors
- 🔗 Support for every model (Llama, Grok, OpenAI, Anthropic, etc.)
- 👥 Multi-agent and room support
- 📚 Easily ingest and interact with your documents
- 💾 Retrievable memory and document store
- 🚀 Highly extensible - create your own actions and clients
- ☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
- 📦 Just works!

## Video Tutorials

[AI Agent Dev School](https://www.youtube.com/watch?v=ArptLpQiKfI&list=PLx5pnFXdPTRzWla0RaOxALTSTnVq53fKL)

## 🎯 Use Cases

- 🤖 Chatbots
- 🕵️ Autonomous Agents
- 📈 Business Process Handling
- 🎮 Video Game NPCs
- 🧠 Trading

## 💰 If you plan to launch a token

This framework is the number one open source project on github, we are enabling the next generation of human-machine interface but we still need your help to ensure the code is of the utmost quality with response rapid to critical issues that will affect our builder community at large.

To ensure sustainable development and continued innovation, we ask contributions of 5-10% of initial token distributions from successful launches.

All contributions are publicly tracked on-chain and used exclusively for ecosystem development.

### ⚠️ Don't forget to tip the big guy 10%: ⚠️
[AM84n1iLdxgVTAyENBcLdjXoyvjentTbu5Q6EpKV1PeG](https://solscan.io/account/AM84n1iLdxgVTAyENBcLdjXoyvjentTbu5Q6EpKV1PeG)

## 🚀 Quick Start

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Use the Starter (Recommended)

```bash
git clone https://github.com/elizaos/eliza-starter.git
cd eliza-starter
cp .env.example .env
pnpm i && pnpm build && pnpm start
```

Once the agent is running, you should see the message to run "pnpm start:client" at the end.
Open another terminal and move to same directory and then run below command and follow the URL to chat to your agent.

```bash
pnpm start:client
```

Then read the [Documentation](https://elizaos.github.io/eliza/) to learn how to customize your Eliza.

### Manually Start Eliza (Only recommended if you know what you are doing)

```bash
# Clone the repository
git clone https://github.com/elizaos/eliza.git

# Checkout the latest release
# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
```

### Start Eliza with Gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/elizaos/eliza/tree/main)

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```

Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON
Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON

### Automatically Start Eliza

This will run everything to set up the project and start the bot with the default character.

```bash
sh scripts/start.sh
```

### Edit the character file

1. Open `packages/core/src/defaultCharacter.ts` to modify the default character. Uncomment and edit.

2. To load custom characters:
    - Use `pnpm start --characters="path/to/your/character.json"`
    - Multiple character files can be loaded simultaneously
3. Connect with X (Twitter)
    - change `"clients": []` to `"clients": ["twitter"]` in the character file to connect with X

### Manually Start Eliza

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

### Community & contact

- [GitHub Issues](https://github.com/elizaos/eliza/issues). Best for: bugs you encounter using Eliza, and feature proposals.
- [Discord](https://discord.gg/ai16z). Best for: sharing your applications and hanging out with the community.
- [Developer Discord](https://discord.gg/3f67SH4rXT). Best for: getting help and plugin development.

## Contributors

<a href="https://github.com/elizaos/eliza/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=elizaos/eliza" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=elizaos/eliza&type=Date)](https://star-history.com/#elizaos/eliza&Date)
