<p align="center">
  <strong>human-machine symbiosis // supercoordination // physical AI // XR agents // computational cognition</strong>
</p>

<p align="center">
  <a href="https://caerii.github.io/caerii-os">
    <img src="./assets/enter-command-deck.gif" alt="Enter the interactive 3D Caerii command deck" />
  </a>
</p>

<p align="center">
  <img src="./profile-3d-contrib/profile-green-animate.svg" alt="3D contribution graph" />
</p>

<p align="center">
  <a href="https://github.com/Caerii?tab=repositories"><strong>browse 190+ repos</strong></a> ·
  <a href="#repos-worth-opening"><strong>jump to the good ones</strong></a> ·
</p>

## hi

I'm Alif. I keep coming back to the same problem: most software treats people as operators sitting in front of a screen, but the interesting work happens in rooms, in bodies, between people, across time. I want to build the interfaces for *that*.

In practice I end up somewhere between XR, brain-computer interfaces, multi-agent systems, and modular robotics. I studied in the US and at DTU in Denmark, did MIT Reality Hack in 2023 and 2026, and now run [Superintelligent Group](https://www.superintelligent.group). Before that I worked through Halcyox. Some of these repos are polished. Most aren't. The messy ones are usually the most recent.

Right now I advise engineering at [Doppel Labs](https://www.doppellabs.ai/) and [Wallace](https://www.wallace.so/). I’m also collaborating with [Augmentiv Labs](https://www.augmentivlabs.com/) on a scientific reproducibility stack that uses smartglasses to make lab procedures verifiable and repeatable. Previously, I was the first engineer at [FabuBlox](https://www.fabublox.com/) (MIT Media Lab nanotech spinout), Nov 2024–Aug 2025.

I also once prompted AI to generate [a dating website for worms](https://slitherin.vercel.app/) and [inspired someone to stageplay my AI-generated youtube dialogues at an off-broadway theater in Brooklyn](https://github.com/Caerii/AI_Dialogues_2022), so calibrate accordingly.

## breadth (fast scan)

If you’re trying to understand range quickly: this account is a mix of XR prototypes, research code, web tools, civic projects, and odd art experiments. The list below is curated, but the repo index is the real proof: [`github.com/Caerii?tab=repositories`](https://github.com/Caerii?tab=repositories).

## active threads

| project | what | status |
| --- | --- | --- |
| Superintelligent.Group | swarm multiplayer IDE | building |
| [MosaicDrone](https://github.com/Caerii/MosaicDrone) | modular self-assembling drone swarm | designing |
| Assemblies / NEMO | computational cognition (assembly calculus) | researching |
| [CommonQuant](https://www.commonquant.com/) | market agent societies | testing |
| Unionize.Software | worker coordination tools | organizing |

## repos worth opening

If you only open a few things, open the repos whose **notes** tell you how to run it / what to click / what artifact to look at first.

### coordination & multi-agent infrastructure

| repo | what | notes |
|---|---|---|
| [**superintelligent.group**](https://superintelligent.group/) | swarm-native collaborative software development environment | open `docs/architecture/CONCEPTUAL_OVERVIEW.md` for the “VAC” model |
| **git2.org** | swarm-native version control built on git | run `git2-mcp`; entity-level locking + intent-aware commits |
| **arxiv2.org** | “paper → living project” bridge (paste arXiv URL/ID) | start with `docker compose up` (web+api), then hit `/api/resolve` |
| [**SwarmIDE-Alpha**](https://github.com/Caerii/SwarmIDE-Alpha) | collaborative doc + editor where agents work *in the same space as you* | start `pnpm run server` + `pnpm run dev` (Monaco + Yjs/Y-Sweet) |
| [**AI-ID**](https://github.com/Caerii/AI-ID) | user-owned context layer for AI apps (auth + scoped memory grants) | open `ai-id-app/`; scopes + store/retrieve APIs; optional pgvector |
| [**Unionize.Software**](https://www.unionize.software) | privacy-first worker decision-routing + encrypted organizer intake | open the guides corpus via the shipped CLI + local MCP server |

### mechanistic interpretability & computational cognition

| repo | what | notes |
|---|---|---|
| [**circuit-tracer**](https://github.com/Caerii/circuit-tracer) | find/visualize/intervene on circuits using transcoder features | open `demos/circuit_tracing_tutorial.ipynb` (end-to-end) |
| [**CollaborationCircuitsMechInterp**](https://github.com/Caerii/CollaborationCircuitsMechInterp) | social cognition / ToM circuits in LLMs (multi-agent settings) | open `EXPERIMENTAL_PLAN.md` + `METHODOLOGY.md` first |
| [**assemblies**](https://github.com/Caerii/assemblies) | neural assembly calculus runtime + research workspace (`neural-assemblies`) | run `uv run python examples/01_basic_assembly_calculus.py` |
| [**TYPHON**](https://github.com/Caerii/TYPHON) | hierarchical memory research harness for long-context / cross-episode eval | run `uv run typhon evaluate-memory-suite ...` (docs have runbooks) |
| [**SocietyofScientists**](https://github.com/Caerii/SocietyofScientists) | multi-agent grant proposal generator (AG2 + AI21 Jamba + Exa) | start backend, then `frontend/` → wizard; export PDF/DOCX/LaTeX |
| [**feb_2_26_multi_agent_research**](https://github.com/Caerii/feb_2_26_multi_agent_research) | local 407-paper multi-agent research corpus + tools | run `python search_papers.py \"keyword\"` |

### XR / wearables / embodied interfaces

| repo | what | notes |
|---|---|---|
| [**OpenGalea**](https://github.com/Caerii/OpenGalea) | colocated multiplayer MR controlled by EEG (OpenBCI Cyton + Quest 3) | open Devpost/demo links in the README; hardware + setup sections are real |
| [**codrawer-bridge**](https://github.com/Caerii/codrawer-bridge) | Remarkable Paper Pro strokes → AI ghost-layer ink (co-drawing infra) | start at `docs/protocol.md` + `docs/latency_budget.md` |
| [**DelightfulOS**](https://github.com/delightfulvision/DelightfulOS) | “internet of bodies” OS: sensors → signal bus → policies → AR overlays | run demo script, then open the dashboard (`/dashboard`) |
| [**OpenEgoLens**](https://github.com/Caerii/OpenEgoLens) | hackable egocentric camera gateway (stream + control + AI snapshots) | run gateway + UI; frame sampling (1–2s) is the core design choice |
| [**LifeInBetweenXR**](https://github.com/Caerii/LifeInBetweenXR) | MIT Reality Hack 2023 3D map viewer | open and run the Unity project |
| [**MicrocosmXR**](https://github.com/Caerii/MicrocosmXR) | multiplayer XR sandbox for shared world-building | explore Unity project + Minecraft integration experiments |
| [**WearableHolographicTheatreKid**](https://github.com/Caerii/WearableHolographicTheatreKid) | wearable holographic theater piece | open the repo and skim the artifacts |

### robotics / CAD / sim-to-real

| repo | what | notes |
|---|---|---|
| [**OpenCAD**](https://github.com/Caerii/OpenCAD) | modular CAD stack: kernel + solver + feature-tree + agent + viewport | start viewport in mock mode, then flip `VITE_USE_MOCK=false` for live services |
| [**SimCorrect**](https://github.com/Caerii/SimCorrect) | autonomous sim-model fault detection + correction loop | run a `Problem*_*/demo.py` to watch detect → fix → verify |
| [**MosaicDrone**](https://github.com/Caerii/MosaicDrone) | “programmable aerial voxels” — modular self-assembling omnidirectional drone swarm | start at “MOSAIC defined” + architecture diagrams in the README |
| [**OpenEnvironment**](https://github.com/Caerii/OpenEnvironment) | natural language → procedural 3D terrain (heightmaps/splatmaps/voxels) | start backend + web, then try the example prompts (“create a desert…”) |

### web / products / odd but real

| repo | what | notes |
|---|---|---|
| [**VisuaML**](https://visuaml.com/) | visual ML editor on the web | open the live site, then the repo for implementation |
| [**CommonQuant.com**](https://www.commonquant.com/) | AI-powered market analysis web platform | start the web app and click through the core flows |
| [**3d-audio-visualizer**](https://github.com/Caerii/3d-audio-visualizer) | 3D acoustic wave visualization sandbox | start `pnpm dev`; open `src/visualization/IsometricWaveScene.tsx` |
| [**slither.in**](https://slitherin.vercel.app/) | dating site for worms + tiny arcade game | open the live site; “Squiggle” is the hidden proof-of-craft |
| [**smartsight-backend**](https://github.com/Caerii/smartsight-backend) | backend for SmartSight accessibility/vision project | skim routes/services; it’s real backend glue work |
| [**TheBabelBook**](https://github.com/Caerii/TheBabelBook) | Library of Babel, but with GPT-3 | open the README + core generation logic |
| [**criticaltheory-wiki**](https://criticaltheory.wiki/) | applied critical theory wiki | open the live wiki, then the repo for content mechanics |
| [**fast360compression**](https://github.com/Caerii/fast360compression) | saliency-based 360° video compression research code | run/skim the core C pipeline and results |

### index (the wider perimeter)

This is the “everything else” map — classes, prototypes, websites, one-offs, and experiments that still say something true about how I build.

- **websites & products**
  - [**alifjakir.com**](https://www.alifjakir.com/): my personal experimental blog where I go more into detail on things!
  - [**nanotech.school**](https://www.nanotech.school/): interactive web learning for nanotech (work in progress).
  - [**theaicodecompany.com**](https://www.theaicodecompany.com/): currently a concept for a portable virtual AI company.
  - [**Caerii.github.io**](https://github.com/Caerii/Caerii.github.io): older GitHub Pages site / web presence experiments.
  - [**CommonQuant.com**](https://github.com/Caerii/CommonQuant.com): the CommonQuant marketing site/app codebase (Next.js).

- **multi-agent / LLM experiments**
  - [**AgentMultiverse**](https://github.com/Caerii/AgentMultiverse): experiments with OpenAI Assistants-era agent wiring.
  - [**LanguageAgentTreeSearch**](https://github.com/Caerii/LanguageAgentTreeSearch): notes/implementation around agentic planning via tree search.
  - [**pdf-parser-ai**](https://github.com/Caerii/pdf-parser-ai): “parse PDFs intelligently” prototype.
  - [**PDFScraper**](https://github.com/Caerii/PDFScraper): brute-force PDF scraping when you just need the text out.
  - [**AutoTasker**](https://github.com/Caerii/AutoTasker): automatic data annotation / task automation experiments.

- **robotics-ish / systems**
  - [**DroneDesign**](https://github.com/Caerii/DroneDesign): early sketches toward flying-robot design thinking.
  - [**CS444-Final-DiningPhilsophers**](https://github.com/Caerii/CS444-Final-DiningPhilsophers): concurrency fundamentals (dining philosophers).
  - [**CS444-HW1**](https://github.com/Caerii/CS444-HW1): parallel thread multiplication (threads + performance basics).
  - [**CS444-HW2**](https://github.com/Caerii/CS444-HW2): producer/consumer with mutexes (synchronization practice).
  - [**CS444-HW3**](https://github.com/Caerii/CS444-HW3): keylogger (OS-level input capture exploration).

- **graphics / rendering / play**
  - [**-CS452-ComputerGraphicsClass**](https://github.com/Caerii/-CS452-ComputerGraphicsClass): graphics class work (a trail of shaders and geometry).
  - [**TheMysteryRoom3D**](https://github.com/Caerii/TheMysteryRoom3D): a small 3D world / interactive space experiment.
  - [**GraphicsGame**](https://github.com/Caerii/GraphicsGame): JavaScript graphics class final (absorb-everything game).

- **audio / media**
  - [**3d-audio-visualizer**](https://github.com/Caerii/3d-audio-visualizer): a sandbox for 3D audio waveform visualization.
  - [**checkmysoundcloud**](https://github.com/Caerii/checkmysoundcloud): music-and-vibes portfolio experiments.
  - [**IS426_Audio2Spectrogram**](https://github.com/Caerii/IS426_Audio2Spectrogram): audio → spectrogram preprocessing pipeline.

- **hackathons / prototypes**
  - [**LifeInBetweenXR**](https://github.com/Caerii/LifeInBetweenXR): MIT Reality Hack 2023 3D map viewer sprint.
  - [**EmergencyAIHelper**](https://github.com/Caerii/EmergencyAIHelper): HIPAA-ish on-prem emergency AI agents prototype for first responders.
  - [**Zaqathon-submission**](https://github.com/Caerii/Zaqathon-submission): hackathon submission repo (prototype snapshot).

- **small utilities / coursework**
  - [**XMLParser**](https://github.com/Caerii/XMLParser): simple XML parser (parser-building practice).
  - [**Typescript-Calculator**](https://github.com/Caerii/Typescript-Calculator): does what it says on the tin.
  - [**cs460-backend-webapp**](https://github.com/Caerii/cs460-backend-webapp): backend webapp coursework repo.
  - [**CodePathAndroidPrework**](https://github.com/Caerii/CodePathAndroidPrework): early Android/Kotlin learning app.

- **weird artifacts**
  - [**EnviroVoiceImpersonator-EVI**](https://github.com/Caerii/EnviroVoiceImpersonator-EVI): “stick it on objects and it’ll talk” local model physical object "hat" prototype energy.
  - [**slither.in**](https://slitherin.vercel.app/): the worm dating website (yes, really).
  - [**AI_Dialogues_2022**](https://github.com/Caerii/AI_Dialogues_2022): AI-generated dialogues staged as theater.

### complete repo index (auto-generated)

This is a machine-generated index of my owned repos (sorted by most recent pushes). It’s intentionally exhaustive; the sections above are the human-curated reading path.

<details>
<summary><strong>open the full repo index (auto-generated)</strong></summary>

| repo | what | lang |
|---|---|---|
| [slither.in](https://slitherin.vercel.app/) | a dating website for worms | JavaScript |
| [CommonQuant.com](https://www.commonquant.com/) | AI quantitative trading for everyone | TypeScript |
| [Caerii](https://github.com/Caerii/Caerii) | All about Alif's funky wunky stuff |  |
| [codrawer-bridge](https://github.com/Caerii/codrawer-bridge) | A low-latency, stroke-native “co-drawer” bridge: reMarkable Paper Pro streams pen strokes to a desktop server; desktop triggers an AI... | Python |
| [TYPHON](https://github.com/Caerii/TYPHON) | hierarchical cross-episodic associative memory | Python |
| [3d-audio-visualizer](https://github.com/Caerii/3d-audio-visualizer) | standalone 3d audio wave visualization sandbox | TypeScript |
| [alifjakir.com](https://www.alifjakir.com/) | My Personal Site |  |
| [CollaborationCircuitsMechInterp](https://github.com/Caerii/CollaborationCircuitsMechInterp) | Mechanistic Interpretability of Multi-Agent Collaboration! | Python |
| [OpenGalea](https://github.com/Caerii/OpenGalea) | An Open-Source Mixed Reality Brain Computer Interface! Won 5 Quest's from Meta from MIT Reality Hack 2025 for this! |  |
| [VisuaML](https://visuaml.com/) | Visual Machine Learning editor on the web bridging category theory, compilers, scientific approaches to AutoML | TypeScript |
| [MosaicDrone](https://github.com/Caerii/MosaicDrone) | A modular, self-assembling omnidirectional drone swarm | Python |
| [CS444-Final-DiningPhilsophers](https://github.com/Caerii/CS444-Final-DiningPhilsophers) | C++ Program that solves the dining philosopher's problem. | C++ |
| [Task-Matrix-Flow](https://github.com/Caerii/Task-Matrix-Flow) | Repository for https://replit.com/@AlJ3/Task-Matrix-Flow | TypeScript |
| [feb_2_26_multi_agent_research](https://github.com/Caerii/feb_2_26_multi_agent_research) | research tranch | Python |
| [MicrocosmXR](https://github.com/Caerii/MicrocosmXR) | MicrocosmXR is a multiplayer XR sandbox with semantic scene understanding for being gods of a virtual civilization. | C# |
| [OpenAlterEgo-v0.2](https://github.com/Caerii/OpenAlterEgo-v0.2) | test draft of open alter ego, for silent speech interfacing | Python |
| [LaborRightsNYC](https://github.com/Caerii/LaborRightsNYC) | Reforming labor in NYC - evidence and data | TypeScript |
| [LifeInBetweenXR](https://github.com/Caerii/LifeInBetweenXR) | Reality Hack 2023 3D Map Viewer | C# |
| [smartsight-backend](https://github.com/Caerii/smartsight-backend) | spinoff smartsight | JavaScript |
| [smartsight-ios](https://github.com/Caerii/smartsight-ios) | spinoff smartsight |  |
| [3D-Web-Sandbox](https://github.com/Caerii/3D-Web-Sandbox) | Physics sandbox in the web! | Makefile |
| [AI-ID](https://github.com/Caerii/AI-ID) | Personalized qualitative user context layer for AI apps | TypeScript |
| [criticaltheory-wiki](https://criticaltheory.wiki/) | a wiki for the new era of applied critical theory | MDX |
| [theaicodecompany.com](https://www.theaicodecompany.com/) | concept for a portable virtual AI company | TypeScript |
| [unlinkedin.org](https://www.unlinkedin.org/) | work clicker. | TypeScript |
| [OpenEnvironment](https://github.com/Caerii/OpenEnvironment) | natural language driven game environment generation system | Python |
| [SwarmIDE-Alpha](https://github.com/Caerii/SwarmIDE-Alpha) | flow-state enhancing multi-agent project creation | TypeScript |
| [Caerii.github.io](https://github.com/Caerii/Caerii.github.io) |  | HTML |
| [nanotech.school](https://www.nanotech.school/) | intuitive ways to learn nanotechnology on the web | TypeScript |
| [sylashorowitz](https://github.com/Caerii/sylashorowitz) | Personal portfolio website | JavaScript |
| [pdf-parser-ai](https://github.com/Caerii/pdf-parser-ai) | test module to parse PDFs intelligently | TypeScript |
| [Kernel-Optimization-Puzzles](https://github.com/Caerii/Kernel-Optimization-Puzzles) | Kernel Optimization Challenges | Python |
| [Carbon-Fee-and-Dividend-Simulator](https://github.com/Caerii/Carbon-Fee-and-Dividend-Simulator) | carbon fee simulator for changing mass state level policy | Python |
| [Zaqathon-submission](https://github.com/Caerii/Zaqathon-submission) |  | TypeScript |
| [High-Frequency-Financial-Modeling-Python](https://github.com/Caerii/High-Frequency-Financial-Modeling-Python) | For our own learning and experimentation on financial information | Python |
| [Massive-Multiplayer-Vibe-Coding](https://github.com/Caerii/Massive-Multiplayer-Vibe-Coding) | A novel paradigm for multiplayer vibe coding |  |
| [StigmergySimulator](https://github.com/Caerii/StigmergySimulator) | cool shader toys |  |
| [Thinkstruct-Neural-Query](https://github.com/Caerii/Thinkstruct-Neural-Query) | Private Vector DB | TypeScript |
| [aaausbangla.com](https://github.com/Caerii/aaausbangla.com) | US Bengali Tourism website | TypeScript |
| [Time-Analyzer](https://github.com/Caerii/Time-Analyzer) | Life analytics dashboard stuff | Python |
| [StudentSites](https://github.com/Caerii/StudentSites) | My student's websites | TypeScript |
| [Team16-Hackathon.Bio](https://github.com/Caerii/Team16-Hackathon.Bio) | Automatic Data Scientist Society of Agents |  |
| [Artificialgeneralintelligence-dev-website](https://github.com/Caerii/Artificialgeneralintelligence-dev-website) | AGI Dev community | JavaScript |
| [Identicon-Generator-Site](https://github.com/Caerii/Identicon-Generator-Site) | Creating identicons automatically! | TypeScript |
| [Locus](https://github.com/Caerii/Locus) | This creates a novel process for accelerating utility infrastructure siting through real-time, comprehensive data access, communities, an... |  |
| [fast360compression](https://github.com/Caerii/fast360compression) | Georgia State University - REU 2021 Saliency Based Compression Technique for 360 Videos | C |
| [GrimRepo](https://github.com/Caerii/GrimRepo) | Alif and Eloise killed the repository |  |
| [RecipeCalculator](https://github.com/Caerii/RecipeCalculator) | Help plan recipes and meals over weeks to make sure you get all nutrients in! | Python |
| [Clarkson-Google-Dev-Site](https://github.com/Caerii/Clarkson-Google-Dev-Site) | Maintaining the Website for it's evolution into the MIT GDSC | JavaScript |
| [WhyHowBeta](https://github.com/Caerii/WhyHowBeta) | Experimental Implementation of WhyHow.AI Graph Toolkits for AI Understanding | Python |
| [InvestComply](https://github.com/Caerii/InvestComply) | prototype | Python |
| [EmergencyAIHelper](https://github.com/Caerii/EmergencyAIHelper) | HIPPA Compliant On-Premise Emergency AI Agents Prototype Implementation for First Responders to create effort reduction for those in real... |  |
| [WearableHolographicTheatreKid](https://github.com/Caerii/WearableHolographicTheatreKid) | Epic wearable theatre kid made by Alif Jakir & Sylas Horowitz | JavaScript |
| [suno-api](https://github.com/Caerii/suno-api) |  | TypeScript |
| [Scratchpad](https://github.com/Caerii/Scratchpad) | Just some testing stuff |  |
| [EmberAlifGame-RenameLater](https://github.com/Caerii/EmberAlifGame-RenameLater) | Experimental Implementations for an interesting game-thing! Add more desc. later! | ReScript |
| [AutoTasker](https://github.com/Caerii/AutoTasker) | Automatically Does Data Annotation Tasks |  |
| [checkmysoundcloud](https://github.com/Caerii/checkmysoundcloud) | Music and Vibes portfolio | JavaScript |
| [Obscure-Trial](https://github.com/Caerii/Obscure-Trial) | Hypothetical Gumroad Design | CSS |
| [DroneDesign](https://github.com/Caerii/DroneDesign) | We explore new frontiers in flying robots! |  |
| [AgentMultiverse](https://github.com/Caerii/AgentMultiverse) | Alif Jakir and Ryan Tran's experiments with OpenAI Assistants | Python |
| [PDFScraper](https://github.com/Caerii/PDFScraper) | It scrapes PDFs, what more do you want? | Python |
| [AlexAlifThoughts](https://github.com/Caerii/AlexAlifThoughts) | A repository of thoughts and directions for future research |  |
| [LanguageAgentTreeSearch](https://github.com/Caerii/LanguageAgentTreeSearch) | LANGUAGE AGENT TREE SEARCH UNIFIES REASONING ACTING AND PLANNING IN LANGUAGE MODELS |  |
| [EnviroVoiceImpersonator-EVI](https://github.com/Caerii/EnviroVoiceImpersonator-EVI) | Stick it on objects and stuff! It’ll talk… or else |  |
| [-CS452-ComputerGraphicsClass](https://github.com/Caerii/-CS452-ComputerGraphicsClass) | Some cool stuff that I did in class! | JavaScript |
| [TheBabelBook](https://github.com/Caerii/TheBabelBook) | The Library of Babel, now with GPT-3! | Python |
| [Low-Light-Enhancement-GAN](https://github.com/Caerii/Low-Light-Enhancement-GAN) | DTU Computational Photography Project | Python |
| [Photonics_Processing](https://github.com/Caerii/Photonics_Processing) | For July 2023 Denmark Technical University Machine Vision Course |  |
| [Typescript-Calculator](https://github.com/Caerii/Typescript-Calculator) | does what it says on the tin |  |
| [CS473-ComputerVisionClass](https://github.com/Caerii/CS473-ComputerVisionClass) | Here are ways that we made computers see! | Python |
| [cs460-backend-webapp](https://github.com/Caerii/cs460-backend-webapp) |  | JavaScript |
| [CS444-HW3](https://github.com/Caerii/CS444-HW3) | Keylogger | C++ |
| [XMLParser](https://github.com/Caerii/XMLParser) | Simple Parser for XML documents | Python |
| [AI_Dialogues_2022](https://github.com/Caerii/AI_Dialogues_2022) | Performed As a Play on 2/26/23 in Brooklyn, NYC |  |
| [CS444-HW2](https://github.com/Caerii/CS444-HW2) | Producer Consumer Problem with mutexes | C++ |
| [CS444-HW1](https://github.com/Caerii/CS444-HW1) | Parallel Thread Multiplication | C++ |
| [CodePathAndroidPrework](https://github.com/Caerii/CodePathAndroidPrework) | Simple silly android application for learning purposes | Kotlin |
| [DolbyVideoCallDemoTestXR](https://github.com/Caerii/DolbyVideoCallDemoTestXR) |  | TypeScript |
| [Logseq](https://github.com/Caerii/Logseq) | Up to date Logseq for my second digital brain |  |
| [IS426_Audio2Spectrogram](https://github.com/Caerii/IS426_Audio2Spectrogram) | Processes audio into usable spectrograms for classification | Python |
| [TheMysteryRoom3D](https://github.com/Caerii/TheMysteryRoom3D) | This room is unlike any you've ever seen before. |  |
| [GraphicsGame](https://github.com/Caerii/GraphicsGame) | A game for our CS452 Graphics Class. You are the president of the school and you need to absorb everyone and everything. | JavaScript |
| [ClackPublic](https://github.com/Caerii/ClackPublic) | Allows for Client-Server Communication with a GUI | HTML |
| [LogseqOld](https://github.com/Caerii/LogseqOld) | All my networked notes! |  |
| [GPT3WebSummarizer](https://github.com/Caerii/GPT3WebSummarizer) | Create easy summaries of web content. | C# |
| [logseq-1](https://github.com/Caerii/logseq-1) | A privacy-first, open-source platform for knowledge sharing and management. | Clojure |
| [GitHelloDate](https://github.com/Caerii/GitHelloDate) | Testing Github | Java |

</details>

<details>
<summary><strong>open the forks index (top recent)</strong></summary>

Forks of things I am exploring, working on contributions to, or are saving (sorted by recent pushes; top 60 shown).

| repo | what | lang |
|---|---|---|
| [agents-are-thinking](https://github.com/Caerii/agents-are-thinking) | A weekend project exploring agent "thinking" animation. | Python |
| [WaveletLM](https://github.com/Caerii/WaveletLM) | WaveletLM | Python |
| [vortexnet](https://github.com/Caerii/vortexnet) | VortexNet: Neural Computing through Fluid Dynamics | Python |
| [ast-outline](https://github.com/Caerii/ast-outline) | Fast, AST-based structural outline for source files. Built for LLM coding agents and humans. | Rust |
| [LogseqVisionClaw](https://github.com/Caerii/LogseqVisionClaw) | Logseq Spring Thing Immersive & Agentic Knowledge Development Engine | Rust |
| [TileKernels](https://github.com/Caerii/TileKernels) | A kernel library written in tilelang | Python |
| [fleetmdm](https://github.com/Caerii/fleetmdm) | Open device management (live: https://fleetdm.com) | Go |
| [spikingjelly](https://github.com/Caerii/spikingjelly) | SpikingJelly is an open-source deep learning framework for Spiking Neural Network (SNN) based on PyTorch. (live: https://spikingjelly.readthedocs.io) | Python |
| [minebench](https://github.com/Caerii/minebench) | Minecraft-style voxel benchmark for comparing AI models (Arena + Sandbox) (live: https://minebench.ai) | TypeScript |
| [late-sh](https://github.com/Caerii/late-sh) | A cozy terminal clubhouse for developers. Lofi beats, casual games, chat, and tech news, all via SSH. (live: https://late.sh) | Rust |
| [catgrad](https://github.com/Caerii/catgrad) | a categorical deep learning compiler | Rust |
| [ZWM](https://github.com/Caerii/ZWM) | Zero-shot World Models Are Developmentally Efficient Learners | Python |
| [obsidian-wiki](https://github.com/Caerii/obsidian-wiki) | Framework for AI agents to build and maintain an Obsidian wiki using Karpathy's LLM Wiki pattern | Python |
| [codex](https://github.com/Caerii/codex) | Lightweight coding agent that runs in your terminal | Rust |
| [claude-mem](https://github.com/Caerii/claude-mem) | A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude'... (live: https://claude-mem.ai) | TypeScript |
| [og-logseq](https://github.com/Caerii/og-logseq) | Logseq og (file version) (live: https://logseq.com) | Clojure |
| [open-agents](https://github.com/Caerii/open-agents) | An open source template for building cloud agents. (live: https://open-agents.dev) | TypeScript |
| [b3d](https://github.com/Caerii/b3d) | Bayes3D | Jupyter Notebook |
| [bayes3d](https://github.com/Caerii/bayes3d) |  (live: https://probcomp.github.io/bayes3d/) | Jupyter Notebook |
| [stretchystudio](https://github.com/Caerii/stretchystudio) | FOSS 2D animation tool for turning static illustrations into mesh-deformable characters (live: https://stretchy.studio) | JavaScript |
| [-Project-Nord-Spiking-Neural-Network-Language-Model](https://github.com/Caerii/-Project-Nord-Spiking-Neural-Network-Language-Model) | The first pure SNN language model trained from scratch with a fully original architecture. 618M parameters • 93% sparsity • Runs on p... (live: https://www.nord-ai.net/) | Python |
| [rattles](https://github.com/Caerii/rattles) | 🪇 Minimal terminal spinners for Rust (live: https://docs.rs/rattles) | Rust |
| [promnesia](https://github.com/Caerii/promnesia) | Another piece of your extended mind (live: https://beepb00p.xyz/promnesia.html) | Python |
| [neuroskill](https://github.com/Caerii/neuroskill) | NeuroSkill™ — State of Mind Brain-Computer Interface system (live: https://neuroskill.com) | Rust |
| [playcanvas-engine](https://github.com/Caerii/playcanvas-engine) | Powerful web graphics runtime built on WebGL, WebGPU, WebXR and glTF (live: https://playcanvas.com) | JavaScript |
| [zigzag](https://github.com/Caerii/zigzag) | fast source code documentation (live: https://zagforge.com/) | Zig |
| [graphiti](https://github.com/Caerii/graphiti) | Build Real-Time Knowledge Graphs for AI Agents (live: https://help.getzep.com/graphiti) | Python |
| [xrtracker-package](https://github.com/Caerii/xrtracker-package) | AR object tracking plugin for Unity. Supports AR Foundation (iOS/Android) and desktop webcams. Silhouette, depth, and edge-based tracking... | C# |
| [zep-python](https://github.com/Caerii/zep-python) | Build Agents That Recall What Matters.  Systematically engineer relevant context from chat history & business data. (Python Client) (live: https://help.getzep.com) | Python |
| [playcanvas-web-sdk](https://github.com/Caerii/playcanvas-web-sdk) | Gracia Web SDK | HTML |
| [tribev2](https://github.com/Caerii/tribev2) | This repository contains the code to train and evaluate TRIBE v2, a multimodal model for brain response prediction | Jupyter Notebook |
| [pretext](https://github.com/Caerii/pretext) |  | TypeScript |
| [titans-trainer](https://github.com/Caerii/titans-trainer) | Train TITANS models in 5 lines. Huggingface-style trainer for the TITANS architecture - transformers with neural long-term memory & test-... | Python |
| [eips](https://github.com/Caerii/eips) | The efficient, intention-preserving sequence CRDT. Guaranteed logarithmic-time operations. | Rust |
| [git4aiagents](https://github.com/Caerii/git4aiagents) | All reasoning is stored in git. No external server. No database. No account. No hosting.  Any developer on any system pulls the latest co... (live: https://www.git4aiagents.com/) | Python |
| [ironclaw](https://github.com/Caerii/ironclaw) | IronClaw is OpenClaw inspired implementation in Rust focused on privacy and security (live: https://www.ironclaw.com) | Rust |
| [dioxus](https://github.com/Caerii/dioxus) | Fullstack app framework for web, desktop, and mobile. (live: https://dioxuslabs.com) | Rust |
| [mmr](https://github.com/Caerii/mmr) | Python based algorithmic trading platform for Interactive Brokers | Python |
| [hyperspace-db](https://github.com/Caerii/hyperspace-db) | [H] HyperspaceDB is a high-performance, hyperbolic vector database written in Rust. It features 1-bit quantization, async replication, an... | Rust |
| [ngrep](https://github.com/Caerii/ngrep) | grep plus word embeddings | Rust |
| [LabClaw](https://github.com/Caerii/LabClaw) | LabClaw – Operating Layer for LabOS (Stanford-Princeton AI Co-Scientists) (live: https://labclaw-ai.github.io/) |  |
| [three-geospatial](https://github.com/Caerii/three-geospatial) | Geospatial Rendering in Three.js (live: https://takram-design-engineering.github.io/three-geospatial) | TypeScript |
| [stable-worldmodel](https://github.com/Caerii/stable-worldmodel) | Reliable, minimal and scalable library for evaluating and conducting world model research (live: https://galilai-group.github.io/stable-worldmodel/) | Python |
| [slowrun](https://github.com/Caerii/slowrun) | 100M tokens. Infinite compute. Lowest val loss wins. | Python |
| [scienceclaw](https://github.com/Caerii/scienceclaw) |  | Python |
| [scg_Foundation-1-comfyUI](https://github.com/Caerii/scg_Foundation-1-comfyUI) | ComfyUI nodes for RoyalCities Foundation-1 — structured text-to-sample music generation with full BPM, key, timbre, and FX control | Python |
| [autoresearch-go-ane](https://github.com/Caerii/autoresearch-go-ane) | Autonomous AI research on Apple Silicon using ANE-accelerated training | Go |
| [superml](https://github.com/Caerii/superml) | An ML engineering plugin for your coding agents. (live: https://leeroo.com/) | Python |
| [Infinite](https://github.com/Caerii/Infinite) |  | TypeScript |
| [meetily](https://github.com/Caerii/meetily) | Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization bui... (live: https://meetily.ai) | Rust |
| [ml_forge](https://github.com/Caerii/ml_forge) | A visual-based graph node editor for training computer vision models. | Python |
| [RaTeX](https://github.com/Caerii/RaTeX) |  KaTeX-compatible LaTeX math renderer in pure Rust. No JavaScript, no WebView, no DOM. One Rust core → iOS,          Android, Flutter, ... (live: https://erweixin.github.io/RaTeX/demo/support_table.html) | Rust |
| [causationentropy](https://github.com/Caerii/causationentropy) | Implementation of Causation Entropy from Clarkson Center for Complex Systems Science (C3S2) (live: https://www.clarkson.edu/academics/research/labs-centers/c3s2) | Python |
| [rustdesk](https://github.com/Caerii/rustdesk) | An open-source remote desktop application designed for self-hosting, as an alternative to TeamViewer. (live: https://rustdesk.com) | Rust |
| [Awesome-DLMs](https://github.com/Caerii/Awesome-DLMs) | The official GitHub repo for the survey paper "A Survey on Diffusion Language Models". (live: https://arxiv.org/abs/2508.10875) |  |

</details>

[website](https://www.alifjakir.com/) · [email](mailto:alif@superintelligent.group) · [linkedin](https://www.linkedin.com/in/alif-jakir)
