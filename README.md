<a align="center" href="https://github.com/HarshS1611"><img src="./assets/profile1.gif" alt="Harsh profile banner" width="100%"/></a>

<p align="center">
  <a href="https://github.com/HarshS1611">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=7CEBF5&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Harsh+Singh+%F0%9F%91%8B;Full+stack+engineer+%E2%86%92+AI+and+ML;Shipping+on+Solana+with+Anchor+%2B+Rust;Neural+nets+from+scratch+in+PyTorch;Solana+security+%7C+Rektoff+cohort+6" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harsh-singh-7993bb1a3/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/harshS_16"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:harshsingh16d@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Based_in-Bangalore%2C_India-7cebf5?style=for-the-badge" alt="Based in Bangalore"/>
</p>

---

### 👋 About me

I'm a full stack engineer with **3 years of production experience** building web apps, DeFi platforms and AI-powered products. I'm now going deep on machine learning from first principles, building neural networks from scratch, on my way into AI safety work.

Open to remote roles, and to relocating for the right role or fellowship.

### 🔭 Right now

| | |
|---|---|
| 🧠 **Learning** | Andrej Karpathy's *Zero to Hero*: micrograd → makemore → GPT, built from scratch |
| 🔐 **Training** | Rektoff Solana Security Bootcamp, cohort 6 |
| 💼 **Looking for** | AI engineering and AI safety roles, remote or with relocation |

---

### 📌 Featured projects

<p align="center">
  <a href="https://github.com/HarshS1611/makemore"><img width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=HarshS1611&repo=makemore&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&text_color=c9d1d9&border_color=7cebf5&border_radius=10" alt="makemore"/></a>
  <a href="https://github.com/HarshS1611/elementaryGPT"><img width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=HarshS1611&repo=elementaryGPT&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&text_color=c9d1d9&border_color=7cebf5&border_radius=10" alt="elementaryGPT"/></a>
  <a href="https://github.com/HarshS1611/Aegis"><img width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=HarshS1611&repo=Aegis&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&text_color=c9d1d9&border_color=7cebf5&border_radius=10" alt="Aegis"/></a>
  <a href="https://devfolio.co/projects/flowsend-bac3"><img width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=HarshS1611&repo=base-mini-app&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&text_color=c9d1d9&border_color=7cebf5&border_radius=10" alt="FlowSend"/></a>
</p>

<p align="center"><a href="https://github.com/HarshS1611?tab=repositories"><img src="https://img.shields.io/badge/All_repositories-2962FF?style=for-the-badge&logo=github&logoColor=white" alt="All repositories"/></a></p>

---

### 🧠 AI and ML

<details open>
<summary><b>makemore: character-level language models in PyTorch</b></summary>
<br/>

| Model | Dev loss |
|---|---|
| Bigram (counting) | 2.45 |
| MLP, 10-character context | 2.09 |
| MLP + BatchNorm | **2.04** |

Every model has tests, results across random seeds and an ablation study. → [**HarshS1611/makemore**](https://github.com/HarshS1611/makemore)

</details>

<details>
<summary><b>elementaryGPT: a transformer from scratch that writes like Sherlock Holmes</b></summary>
<br/>

A character-level GPT written from scratch in PyTorch and trained on all nine Sherlock Holmes books. 4.82M parameters, validation loss 1.27, with tests and a reproducible sampler (fixed temperature and seed).

> **Prompt:** "Watson," said Holmes, "<br/>
> **Model:** that good everything must be promised. I should have always put the lady through the situation of the case."

It has learned Conan Doyle's voice (dialogue, Victorian vocabulary, names), not plot or meaning, which is expected at this size. → [**HarshS1611/elementaryGPT**](https://github.com/HarshS1611/elementaryGPT)

</details>

<details>
<summary><b>FlowSend: AI-assisted remittances on Base</b> · <a href="https://flowsend-mini-app-alpha.vercel.app/">live app</a></summary>
<br/>

A remittance app on Base that uses LLM API calls to flag anomalous transfer patterns and suspicious behaviour, with escrow smart contracts built using AgentKit and the CDP SDK. → [**Devfolio**](https://devfolio.co/projects/flowsend-bac3) · [**HarshS1611/base-mini-app**](https://github.com/HarshS1611/base-mini-app)

</details>

---

### ◎ Solana and Web3

<details open>
<summary><b>Aegis: guardian-based key recovery on Solana</b> · <a href="https://aegis-protocol-dusky.vercel.app/">live app</a></summary>
<br/>

A non-custodial vault: if the owner goes inactive, a threshold of guardians can rotate ownership, but guardians never touch the funds. Anchor program in Rust, tested with LiteSVM, with a Next.js frontend. Deployed on Solana devnet. Built during Turbin3 Builders, Q2 2026.

```mermaid
flowchart LR
    O["Owner wallet"] -- "deposit SOL, set guardians,<br/>threshold, inactivity window" --> V[("Vault PDA")]
    G1["Guardian"] -- "approve recovery" --> P["Aegis program"]
    G2["Guardian"] -- "approve recovery" --> P
    P -- "owner inactive and<br/>threshold reached" --> R["Rotate owner"]
    R --> V
```

→ [**HarshS1611/Aegis**](https://github.com/HarshS1611/Aegis)

</details>


### 🌐 Open source

<details>
<summary><b>Protocol Labs, Storacha and DefiLlama</b></summary>
<br/>

- **[DefiLlama](https://github.com/DefiLlama/dimension-adapters/pulls?q=is%3Apr+author%3AHarshS1611):** contributor to fee and volume adapters.
- **Protocol Labs developer grant** (FIL-Builders / Storacha), Jan 2025 to Mar 2026:
  - [**storacha-migration-tool**](https://github.com/HarshS1611/storacha-migration-tool): a TypeScript library that streams files and folders from AWS S3 straight to Storacha, without downloading them locally. Published on npm.
  - [**toju (afara)**](https://github.com/tojunetwork/afara): a crypto-native onramp for decentralized storage on IPFS via Storacha, paid in SOL, USDFC or USDC, with agent payments over x402.
- **Protocol Labs Dev Guild:** participant across cohorts 2 to 6, about 11 months.

</details>

### 🏆 Hackathon wins

**Unfold 2024** · **ETHIndia 2022** · **Mercor Chatbot Challenge 2023** · **E-Hack VIT**

---

### 🧰 Languages and tools

<p align="left">
  <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40"/></a>
  <a href="https://pytorch.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" title="PyTorch" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40"/></a>
  <a href="https://react.dev" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" title="React" width="40" height="40"/></a>
  <a href="https://nextjs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="Next.js" title="Next.js" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" title="Node.js" width="40" height="40"/></a>
  <a href="https://www.rust-lang.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" title="Rust" width="40" height="40"/></a>
  <a href="https://soliditylang.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/solidity/solidity-original.svg" alt="Solidity" title="Solidity" width="40" height="40"/></a>
  <a href="https://www.postgresql.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40"/></a>
  <a href="https://www.mongodb.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" title="MongoDB" width="40" height="40"/></a>
  <a href="https://www.docker.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" title="Docker" width="40" height="40"/></a>
  <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" title="AWS" width="40" height="40"/></a>
  <a href="https://git-scm.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" title="Git" width="40" height="40"/></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" alt="Solana"/>
  <img src="https://img.shields.io/badge/Anchor-1E1E1E?style=flat-square" alt="Anchor"/>
  <img src="https://img.shields.io/badge/LiteSVM-1E1E1E?style=flat-square" alt="LiteSVM"/>
  <img src="https://img.shields.io/badge/Foundry-1E1E1E?style=flat-square" alt="Foundry"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
</p>

### 📊 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=HarshS1611&show_icons=true&count_private=true&hide_border=true&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&text_color=c9d1d9" alt="GitHub stats"/>
  <img height="165" src="https://streak-stats.demolab.com?user=HarshS1611&hide_border=true&background=1F222E&ring=7cebf5&fire=2d7de4&currStreakLabel=7cebf5" alt="GitHub streak"/>
</p>

---

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HarshS1611&layout=compact&langs_count=8&hide_border=true&bg_color=1F222E&title_color=7cebf5&text_color=c9d1d9" alt="Top languages"/>
</p>

<p align="center"><i>Happy to talk about machine learning, AI safety or Solana. Reach out on LinkedIn or by email.</i></p>
