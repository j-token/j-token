<div align="center">

# Hi there, I'm j-token

### Full-Stack Developer · AI Tinkerer · Game Maker

![Profile Views](https://komarev.com/ghpvc/?username=j-token&color=brightgreen&style=flat-square&label=Profile+Views)

</div>

---

## About Me

> **"재미있어 보이는 건 참을 수 없습니다!"**

문제 해결을 위해 **협업의 가치와 기술적 깊이**를 중요하게 생각하는 풀스택 개발자입니다.
Node.js(NestJS)와 Python(FastAPI)로 백엔드를 짓고, React / React Native / SvelteKit 으로 웹·앱을 만듭니다.
그리고 LLM이 세상에 막 나왔을 때부터 **로컬 AI 서비스를 직접 운영**해 온 경험을 바탕으로, 요즘은 AI 에이전트 도구를 만드는 데 몰두하고 있습니다.

- AI 코딩 도구(**opencode · Claude · GPT · Codex**)를 적극 활용해 생산성을 극대화합니다
- 부족한 도구는 **직접 MCP 서버·플러그인으로** 만듭니다
- 실시간 통신(WebRTC / MQTT / TCP), 게임 개발(Unity), 협동로봇 제어까지 — 재미있어 보이는 건 일단 건드려 봅니다

> **📋 Disclosure** — 이 프로필에 등장하는 프로젝트 중 **RB-Ware의 로봇 제어 구현만이 AI 도움 없이 단독으로 만든 것**이고, 나머지 모든 작업(실무·개인 사업·사이드 프로젝트·게임)은 Claude·GPT·Codex·opencode 등 AI 코딩 파트너와 협업해 만들어졌습니다. AI는 제가 가장 잘 쓰는 도구이고, **결과물의 품질과 의사결정에 대한 책임은 제가 집니다.**

---

## 관심 분야

> 아래에는 GitHub **공개·비공개 리포를 전수 조사해** 어느 정도 완성된 프로젝트만 추렸습니다.
> 비공개 작업은 방문자 편의를 위해 링크 없이 **(비공개)** 로 표기했습니다.

### 1. AI 에이전트 · MCP · 로컬 LLM

LLM 시대 초창기부터 **로컬 추론 기반 text2sql 서비스**를 개인 사업으로 운영해 왔습니다.
**RWKV-4, LLaMA 1·2** 등 당시 공개된 모델들을 실제 프로덕션에 접목하며 한국어 전처리·토크나이저·학습 데이터 파이프라인을 함께 다뤘습니다.

- 당시 공개 리포: [`extract-text-from-json-by-gjson`](https://github.com/j-token/extract-text-from-json-by-gjson) (AI 학습 데이터 추출) · [`install-mecab-ko-linux`](https://github.com/j-token/install-mecab-ko-linux) (한국어 형태소)
- 오픈소스 기여 (PR): [`alasdairforsythe/tokenmonster`](https://github.com/alasdairforsythe/tokenmonster) (Go SOTA 토크나이저) · [`backnotprop/plannotator`](https://github.com/backnotprop/plannotator) (AI 에이전트 계획 주석·리뷰 도구)
- MCP 서버·플러그인: [`codex-mcp`](https://github.com/j-token/codex-mcp) · [`codex-plugin`](https://github.com/j-token/codex-plugin) · [`claude-agent-mcp`](https://github.com/j-token/claude-agent-mcp) · [`dm-plz`](https://github.com/j-token/dm-plz) · **media-mcp-agents** — FastMCP + Gemini 로 오디오·비디오(YouTube)·이미지·PDF 를 분석하는 멀티모달 MCP 서버 (비공개)
- 에이전트 워크플로우·도구: [`easy-opencode`](https://github.com/j-token/easy-opencode) · [`openclaw`](https://github.com/j-token/openclaw) · [`claude-sync`](https://github.com/j-token/claude-sync) · [`opencode-reviewer`](https://github.com/j-token/opencode-reviewer) (마크다운 드래그-코멘트 리뷰 VSCode 확장)
- **로컬 LLM 양자화 연구** — Qwen3-8B 를 **1.125 bits/weight** 까지 압축하는 1-bit PTQ 파이프라인 직접 구현·실험 (Hadamard rotation + GPTQ + BLoRA, Bonsai 포맷 역분석) (비공개 연구)

### 2. 풀스택 TypeScript & 웹·앱 제품 (NestJS · Next.js · React Native / Expo · SvelteKit · Cloudflare)

- **판도플랫폼 Gen AI 베리어프리 키오스크** — Electron + React + NestJS + GPT Realtime + LiveKit 로 장애인·외국인을 위한 접근성 키오스크 총괄 제작
- **엔피엘솔루션 Better Auth 시스템** — NestJS + Better Auth + PostgreSQL 로 네이버·카카오·구글 로그인 및 계정 연동 구축
- **플레이모어(아미고)** — 앱 결제페이지 제작, Supabase 브랜치로 dev/prod 분리, 회사 홈페이지([ameego.club](https://www.ameego.club/)) 리뉴얼
- **深海月光 -abyssal moonlight- 공식 사이트** — Next.js 16 + PixiJS + Live2D 로 픽셀×Live2D 비주얼 노벨([itch.io](https://garurai.itch.io/abyssalmoonlightprologue))의 공식 사이트 제작, better-auth 화이트리스트 기반 CMS 내장 (비공개)
- **Teru Commission CMS** — Cloudflare Workers + D1 + R2 로 앨범·브랜드 사이트 CMS 풀스택 구축 (비공개)
- **Subkara** — Expo + Supabase + Railway 로 만든 서브컬쳐 노래방 검색 MVP (비공개)
- **실시간 일급 카운터** — Expo / React Native 로 현재 수입을 초 단위로 계산, **Android 포그라운드 서비스**로 앱이 꺼져도 알림 바에서 실시간 갱신 (비공개)
- [`x-twitter`](https://github.com/j-token/x-twitter) — Discord.js + PostgreSQL 로 Bilibili·Twitter/X 미디어 게시글을 Discord 채널에 자동 포스팅하는 모니터 봇
- **개인 사업** — SvelteKit으로 동적 모션 웹툰 사이트 제작 (고세구 트위치 방송 1주년 기념, 현재 비공개)

### 3. 실시간 통신 · 음성 AI (WebRTC · LiveKit · Pipecat · STT/TTS)

- **티와이이엔지** — Go + WebRTC 로 RTSP 카메라 송수신 지연을 **30초 → 1초**로 단축, PTZ 제어 지원
- **판도플랫폼** — GPT Realtime + LiveKit 기반 실시간 음성 키오스크
- **음성 통화 에이전트** — FastAPI + **Pipecat** 파이프라인(STT→LLM→TTS)으로 전화 에이전트 서버 구축, 통화 중 DTMF 키패드 입력 수집까지 처리 (`pipecat-call` / `mire2`, 비공개)
- **RTA (Real-Time Audio Translator)** — Windows 시스템 오디오를 실시간 캡처해 번역·오버레이 자막으로 보여주는 Electron 데스크톱 앱 (Soniox STT 프록시 + Supabase) (비공개)
- **langCAT** — `getDisplayMedia` 화면 공유 오디오를 Deepgram STT + Gemini 번역으로 실시간 이중 자막 표시 (비공개)
- **개인 사업** — Go WebRTC 프레임워크 [**pion**](https://github.com/pion/webrtc)으로 rtsp2webrtc 직접 구현, PTZ 카메라 원격 제어

### 4. 협동로봇 & 산업 자동화 (RB-Ware) — `Solo Build`

**RB-Ware (한국 협동로봇 용접 자동화 1위 · 레인보우로보틱스 파트너)** 에서 1개월간 풀스택 개발자로 참여.

- **Flutter**로 협동로봇 조작 앱 개발, **Unity**로 로봇 티칭/시뮬레이션 UI 구성
- 로봇 ↔ 컨트롤러 간 **TCP / MQTT** 실시간 통신 프로토콜 직접 구현
- **AI 비개입 단독 구현 프로젝트**

### 5. 인증 & OAuth 통합

- 실무: Better Auth + NestJS + PostgreSQL 로 네이버/카카오/구글 연동
- 오픈소스 템플릿: [`better-auth-flutter`](https://github.com/j-token/better-auth-flutter) · [`supabase-custom-oauth-test`](https://github.com/j-token/supabase-custom-oauth-test) (Supabase 네이버 커스텀 OAuth 프로바이더)

### 6. 게임 & 그래픽 (Unity · Godot · Flutter · WebGPU)

**Break Through** — Unity 6.3 URP 기반 3D 타이밍 카운터 액션 게임 (로컬 프로젝트).

- `GameManager` 단일 씬 상태머신, 학습형 적 AI (`EnemyLearningProfile` 바이어스)
- 5단계 공격 타이밍 FSM, 3단 콤보 상태머신, 애니메이션 이벤트 릴레이 패턴
- 토큰 기반 히트스톱 (`TimeScaleController`), 제로 할당 오브젝트 풀링 (`DebrisPool`)
- 커스텀 URP `PixelOutlineFeature` + ToonCrack/Dither 셰이더로 레트로 픽셀 아트
- Aseprite 파이프라인 툴링: [`aseprite-bin`](https://github.com/j-token/aseprite-bin) · [`aseprite_builder`](https://github.com/j-token/aseprite_builder)

**MoonOrBust** — Godot(GDScript) 멀티플레이어 게임. Godot 측 **WebRTC 시그널링 클라이언트/호스트**와 Node.js WebSocket 릴레이·업데이트 매니페스트 서버를 함께 구현, 타입드 데이터 리소스(`PlayerData`/`PositionData`/`DebtData`)로 게임 상태 관리 (비공개)

**경도 (경찰/도둑)** — Flutter + **BLE** 기반 오프라인 근접 감지 술래잡기 앱. GPS 없이 블루투스 신호로만 상대팀을 감지하는 정보 비대칭 설계, Supabase Realtime 으로 게임 상태 동기화 (비공개)

### 7. AI × 금융 (자동매매)

- [`Cryptocurrency_with_ai`](https://github.com/j-token/Cryptocurrency_with_ai) — FastAPI 기반 AI 자동매매 실험
- **Prometheus** — C++20 + Python/FastAPI 로 만든 Bybit 자동매매 시스템. 차트 패턴 인식 + 피보나치 분석 전략, ZeroMQ IPC 로 C++ 코어와 대시보드 분리, SQLite(WAL) 저장 (비공개)

---

## Tech Stack

<div align="center">

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Svelte](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

### Realtime · Protocols

![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-000000?style=for-the-badge&logo=livekit&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![Socket](https://img.shields.io/badge/TCP%20%7C%20WebSocket-4A90E2?style=for-the-badge&logo=socketdotio&logoColor=white)

### Data · Infra

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Game & Graphics

![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge&logo=webgpu&logoColor=white)
![ShaderGraph](https://img.shields.io/badge/URP%20%2F%20ShaderGraph-6E4CFF?style=for-the-badge&logo=unity&logoColor=white)
![Aseprite](https://img.shields.io/badge/Aseprite-7D929E?style=for-the-badge&logo=aseprite&logoColor=white)
![Live2D](https://img.shields.io/badge/Live2D%20%2F%20PixiJS-FF6FA5?style=for-the-badge&logo=pixiv&logoColor=white)

### AI Tools

![Claude](https://img.shields.io/badge/Claude-8B5CF6?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT%20%7C%20Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![opencode](https://img.shields.io/badge/opencode-00D9FF?style=for-the-badge&logo=terminal&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-FF6B35?style=for-the-badge&logo=anthropic&logoColor=white)

</div>

---

## Featured Projects

<div align="center">

| Project                                                                               | Role             | Description                                                |
| ------------------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------- |
| [**easy-opencode**](https://github.com/j-token/easy-opencode)                         | Author           | opencode 쉽게 시작하기 — LSP + AST-grep 플러그인           |
| [**codex-mcp**](https://github.com/j-token/codex-mcp)                                 | Author           | OpenAI Codex SDK MCP 서버 (ChatGPT OAuth)                  |
| [**claude-agent-mcp**](https://github.com/j-token/claude-agent-mcp)                   | Author           | Claude Agent SDK를 래핑한 MCP 서버                         |
| [**dm-plz**](https://github.com/j-token/dm-plz)                                       | Author           | Telegram / Discord로 Claude Code 알림 MCP                  |
| [**x-twitter**](https://github.com/j-token/x-twitter)                                 | Author           | Bilibili·Twitter/X → Discord 미디어 모니터 봇              |
| [**alasdairforsythe/tokenmonster**](https://github.com/alasdairforsythe/tokenmonster) | Contributor (PR) | Go 기반 SOTA 토크나이저 — 로컬 LLM × text2sql 시기의 기여  |
| [**backnotprop/plannotator**](https://github.com/backnotprop/plannotator)             | Contributor (PR) | AI 코딩 에이전트 계획·코드 리뷰 도구                       |
| **media-mcp-agents**                                                                  | Author · 비공개  | FastMCP + Gemini 멀티모달(오디오·영상·이미지·PDF) 분석 MCP |
| **abyssal-moonlight**                                                                 | Author · 비공개  | Next.js 16 + PixiJS/Live2D 비주얼 노벨 공식 사이트 + CMS   |
| **G-Canvas**                                                                          | Author · 비공개  | Tauri v2 + Rust + WebGPU 16K 캔버스 고성능 드로잉          |
| **MoonOrBust**                                                                        | Author · 비공개  | Godot + WebRTC 시그널링 멀티플레이어 게임                  |
| **Prometheus**                                                                        | Author · 비공개  | C++20 + FastAPI Bybit 자동매매 (차트패턴 + 피보나치)       |
| **Break Through**                                                                     | Author · 로컬    | Unity 6.3 URP 3D 타이밍 카운터 액션                        |
| [**Cryptocurrency_with_ai**](https://github.com/j-token/Cryptocurrency_with_ai)       | Author           | FastAPI + AI 자동매매 실험                                 |

</div>

---

## AI-Powered Development

> AI는 도구입니다. 중요한 건 **어떻게 활용하느냐** 입니다.

**Claude + GPT + opencode + Codex = Maximum Productivity**

필요한 도구가 없으면? — **직접 만듭니다.**

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/j-token)
[![Blog](https://img.shields.io/badge/Blog-FF5544?style=for-the-badge&logo=tistory&logoColor=white)](https://i-love-coding.tistory.com/)

</div>

---

<div align="center">

### Thanks for visiting! / 방문해 주셔서 감사합니다!

</div>
