# 👋 김무근 (Michael Kim)

30년 이상 경력의 시니어 소프트웨어 엔지니어 및 시스템 아키텍트입니다.  
현재 Web3 인프라, 스마트 컨트랙트, 블록체인 시스템 설계와 더불어 **AI/LLM 엔지니어링**에 주력하고 있습니다.  
엔터프라이즈 환경을 위한 AI 파이프라인 구축과 Web3 생태계 발전에 기여하고 있습니다.  
공개된 프로젝트는 GitHub과 GitBook을 통해 검증 및 확인 가능합니다.

> 🌐 **[English Version Below](#-english-version)**

----

# 🤖 AI & LLM Engineering

## 🔧 주요 프로젝트 (Notable Projects)

### 1. AutoContent-Pipeline (GenAI 동영상 자동생산 파이프라인)
- 상용 생성형 AI API를 연계한 원스톱 멀티미디어 동영상 자동 생산 소프트웨어입니다[cite: 2].
- **자동화된 멀티모달 오케스트레이션:** 대본 서사 분석 ➔ 컷 분할(Gemini 2.0 Flash) ➔ 이미지 연성(Gemini 3.0 Pro) ➔ 하드웨어 가속 비디오 렌더링(FFmpeg) 파이프라인을 구축했습니다[cite: 2].
- 컷마다 인물/배경이 달라지는 시각적 불일치를 차단하기 위해 **규칙 기반 자가 교정(Self-correction) 검증 알고리즘**과 도메인 특화(조선시대 고증 등) **동적 프롬프트 가드레일**을 독자 설계했습니다[cite: 2].
- 🔗 [GitHub Repository](https://github.com/MichaelKim20/genai-video-pipeline-portfolio)

### 2. AirGapped-LogAI (로컬 LLM 인프라 장애 분석기)
- 외부 인터넷이 완벽히 차단된 100% 폐쇄망(Air-gapped) 엔터프라이즈 환경 전용 로컬 LLM 기반 장애 진단 및 운영 관리 시스템입니다[cite: 1, 3].
- Oracle DB/JEUS 인프라 특화 **정규식 파서**와 ChromaDB 기반의 **RAG 지식 검색 엔진**을 연동하여 AI 환각(Hallucination)을 원천 차단합니다[cite: 1, 3].
- Ollama를 통한 **멀티 모델 동적 라우팅**(Phi-3, Qwen2.5-Coder)을 적용했으며, 분석된 로그와 조치 가이드를 SQLite 기반 KMS로 영구 자산화하여 Zero-Outbound 보안성을 보장합니다[cite: 1, 3].
- 🔗 [GitHub Repository](https://github.com/MichaelKim20/airgapped-log-ai-portfolio)

----

# ⛓️ Smart Contract & Web3 Engineer

## 🔧 주요 프로젝트 (Notable Projects)

### 1. DMS Loyalty Point System
- 프로덕션 레벨의 Web3 연동 포인트 및 메시징 SDK  
- [dms-osx](https://github.com/bosagora/dms-osx), [dms-sdk](https://github.com/bosagora/dms-sdk), [dms-bridge](https://github.com/bosagora/dms-bridge)  
- 📘 [Docs](https://kioscoin.gitbook.io/kios-coin-docs-english)

### 2. Multisig Wallet
- 다자간 승인(Multi-party approval) 로직이 적용된 안전한 스마트 컨트랙트  
- [Contract](https://github.com/bosagora/multisig-wallet)  
- [DApp UI](https://github.com/bosagora/multisig-wallet-app)

### 3. BOSagora ERC-20 Upgrade
- TokenSwap 로직 + Mint/Burn/Pause + 거버넌스 락(Governance lock) 기능 적용  
- [bosagora-erc20](https://github.com/bosagora/bosagora-erc20)

### 4. BOSagora Mainnet
- BOA CoinNet을 위한 이더리움 기반 메인넷 포크(Fork)  
- Execution Layer: [agora-el](https://github.com/bosagora/agora-el)  
- Consensus Layer: [agora-cl](https://github.com/bosagora/agora-cl)  
- 📘 [Documentation](https://docs.bosagora.org/en)

---

## 💼 기술 스택 (Tech Stack)
- **AI & Data:** Python • FastAPI • Streamlit • Ollama (Local LLM) • ChromaDB  
- **Web3 & Backend:** Solidity • Hardhat • Node.js • PostgreSQL • GraphQL • React • TypeScript • Web3Modal • ethers.js

---

# 📈 암호화폐 트레이딩 봇을 위한 기술적 분석 라이브러리 (Python)
알고리즘 암호화폐 트레이딩 시스템에 사용할 수 있는 핵심 기술적 지표들을 구현한 경량 Python 라이브러리입니다.

- 지표: RSI, EMA, MACD, Bollinger Bands 등
- 외부 TA 라이브러리 의존성 없는 100% 순수 Python 구현체
- 시그널 생성, 백테스팅, 실시간 봇 연동에 적합

기존에 개발한 트레이딩 봇과 함께 사용되며 모듈화 및 성능 최적화에 중점을 두었습니다.

🔗 GitHub: https://github.com/MichaelKim20/m-stp

----

## 📫 연락처 (Contact)
📧 [michael.kim.200518@gmail.com](mailto:michael.kim.200518@gmail.com)  
🌐 [github.com/MichaelKim20](https://github.com/MichaelKim20)

<br><br><br>

---

# 🌐 English Version

# 👋 Michael Kim

Senior software engineer with 30+ years of experience.  
Currently focused on Web3 infrastructure, smart contracts, blockchain system design, and AI/LLM engineering.  
Contributing to smart contract infrastructure in the Web3 space and building enterprise-level AI pipelines.  
Public projects are verifiable via GitHub and documented in GitBook.

----

# 🤖 AI & LLM Engineering

## 🔧 Notable Projects

### 1. AutoContent-Pipeline (GenAI Video Pipeline)
- GenAI API-based fully automated multimedia video content generation pipeline.
- Automated multimodal orchestration: Script parsing ➔ Scene Extraction (Gemini 2.0 Flash) ➔ Image Generation (Gemini 3.0 Pro) ➔ Hardware-accelerated Video Synthesis (FFmpeg).
- Features self-correction validation algorithm and domain-specific dynamic prompt guardrails for visual consistency.
- 🔗 [GitHub Repository](https://github.com/MichaelKim20/genai-video-pipeline-portfolio)

### 2. AirGapped-LogAI (Local LLM Log Analyzer)
- 100% Offline (Air-gapped) Local LLM-based enterprise infrastructure diagnostics & operations system.
- Features Regex parsing for Oracle/JEUS errors, ChromaDB RAG pipeline, and multi-model routing (Phi-3, Qwen2.5-Coder) via Ollama.
- Ensures Zero-Outbound data privacy with an SQLite-based KMS for troubleshooting history.
- 🔗 [GitHub Repository](https://github.com/MichaelKim20/airgapped-log-ai-portfolio)

----

# ⛓️ Smart Contract & Web3 Engineer

## 🔧 Notable Projects

### 1. DMS Loyalty Point System
- Production-level Web3-integrated point & messaging SDK  
- [dms-osx](https://github.com/bosagora/dms-osx), [dms-sdk](https://github.com/bosagora/dms-sdk), [dms-bridge](https://github.com/bosagora/dms-bridge)  
- 📘 [Docs](https://kioscoin.gitbook.io/kios-coin-docs-english)

### 2. Multisig Wallet
- Secure smart contract with multi-party approval logic  
- [Contract](https://github.com/bosagora/multisig-wallet)  
- [DApp UI](https://github.com/bosagora/multisig-wallet-app)

### 3. BOSagora ERC-20 Upgrade
- TokenSwap logic + Mint/Burn/Pause + Governance lock  
- [bosagora-erc20](https://github.com/bosagora/bosagora-erc20)

### 4. BOSagora Mainnet
- Ethereum-based mainnet fork for BOA CoinNet  
- Execution Layer: [agora-el](https://github.com/bosagora/agora-el)  
- Consensus Layer: [agora-cl](https://github.com/bosagora/agora-cl)  
- 📘 [Documentation](https://docs.bosagora.org/en)

---

## 💼 Tech Stack
- **AI & Data:** Python • FastAPI • Streamlit • Ollama (Local LLM) • ChromaDB  
- **Web3 & Backend:** Solidity • Hardhat • Node.js • PostgreSQL • GraphQL • React • TypeScript • Web3Modal • ethers.js

---

# 📈 Technical Analysis Library for Crypto Bot (Python)
Developed a lightweight Python library that implements core technical indicators for use in algorithmic crypto trading systems.

- Indicators: RSI, EMA, MACD, Bollinger Bands, and more
- Pure Python implementation with no external TA libraries
- Suitable for signal generation, backtesting, and real-time bot integration

Used in conjunction with my previously built trading bot and designed to be modular and performant.

🔗 GitHub: https://github.com/MichaelKim20/m-stp

----

## 📫 Contact
📧 [michael.kim.200518@gmail.com](mailto:michael.kim.200518@gmail.com)  
🌐 [github.com/MichaelKim20](https://github.com/MichaelKim20)
