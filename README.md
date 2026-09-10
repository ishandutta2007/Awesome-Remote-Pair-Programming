# Awesome-Remote-Pair-Programming

## Top Remote Pair Programming Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Real-Time Collaborative Coding, Screen Sharing for Developers, Co-Editing, Mob Programming & Live Share*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Remote Pair Programming**. These tools enable developers to code together in real time—through low-latency screen sharing with remote control, shared IDE sessions, collaborative editors, or multiplayer coding environments—regardless of physical location.



**Examples** include Tuple, CodeTogether, JetBrains Code With Me, Visual Studio Live Share, Floobits, GitDuck, Replit Multiplayer, CoderPad Live, CodeStream, and Teletype (the category leaders).



**Open-source emphasis**: While polished commercial pairing apps dominate the low-latency desktop experience, there is a growing open-source ecosystem led by **Hopp** (OSS Tuple alternative), collaborative editing frameworks, VS Code/Theia live-share extensions, and real-time coding platforms. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Tuple](https://tuple.app/)**  

  Purpose-built remote pair programming app known for extremely low latency, high-resolution screen sharing, remote control, and a developer-focused experience on macOS, Windows, and Linux.



- **[CodeTogether](https://www.codetogether.com/)**  

  Cross-IDE live share solution supporting VS Code, IntelliJ, Eclipse, and browser guests, with real-time co-editing, debugging, and host-based language intelligence.



- **[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/)**  

  Free real-time collaboration built into Visual Studio and VS Code, enabling shared editing, debugging, terminals, and servers with guests joining via link.



- **[JetBrains Code With Me](https://www.jetbrains.com/code-with-me/)**  

  Collaborative coding, debugging, and screen sharing integrated directly into JetBrains IDEs (availability and support status may vary by product lifecycle).



- **[Replit Multiplayer](https://replit.com/)**  

  Browser-based multiplayer coding environment popular for education, interviews, and lightweight collaborative sessions.



- **[CoderPad Live, Floobits, GitDuck](https://coderpad.io/)**  

  Tools focused on collaborative coding for interviews, real-time co-editing, and pair programming sessions.



- **[CodeStream, Teletype](https://www.codestream.com/)**  

  Additional collaboration layers for code discussion, live sharing, and editor-integrated pairing.



- **[Other pair programming & live-share tools](https://tuple.app/)**  

  Additional commercial solutions covering high-fidelity screen sharing, remote control, and multiplayer IDEs.



## Open-Source GitHub Projects



- **[Hopp](https://github.com/gethopp/hopp)**  

  Leading open-source remote pair programming and screen-sharing app built for developers. Positions itself as an OSS alternative to Tuple, with sub-100ms latency, native desktop clients (Tauri + Rust), and self-hosting support.



- **[Open Collaboration Tools (Eclipse OCT)](https://github.com/eclipse-oct/open-collaboration-tools)**  

  Open-source live-sharing solution for Eclipse Theia, VS Code, and other editors. Enables real-time workspace sharing, cursor/selection awareness, and collaborative editing under the MIT license.



- **[realmeet](https://github.com/piyusharyan/realmeet)**  

  Open-source real-time collaborative coding platform designed for pair programming, technical interviews, code reviews, and training, with low-latency synchronization and multi-language execution.



- **[PairPad](https://github.com/assishmoncs/pairpad)**  

  Full-stack open-source collaborative coding platform with Monaco Editor, CRDT-based concurrent editing, remote cursors, presence, roles, and integrated code execution.



- **[CodeSync and similar CRDT editors](https://github.com/search?q=collaborative+coding+OR+pair+programming+CRDT+OR+Yjs)**  

  Real-time collaborative coding platforms using Yjs or other CRDTs for conflict-free multi-user editing, often with WebRTC audio/video.



- **[PairSync](https://github.com/subev/pairsync)**  

  Tool for live-syncing working files across machines during pair programming so participants can contribute from their own environments.



- **[Other collaborative editor & live-share projects](https://github.com/search?q=live+share+OR+pair+programming+OR+collaborative+IDE)**  

  Community extensions, web-based multiplayer editors, and experimental pairing tools.



- **[Teletype-style & Atom legacy inspiration](https://github.com/search?q=teletype+OR+atom+teletype)**  

  Projects inspired by or continuing the spirit of early collaborative editing experiments.



### Additional Strong Open-Source Options



- **VS Code / Theia collaboration extensions**: Community and official live-share style extensions for real-time co-editing.

- **CRDT libraries**: Yjs, Automerge, and related libraries used as foundations for custom collaborative editors.

- **WebRTC screen-sharing stacks**: Open components for building low-latency developer-focused screen sharing and remote control.

- **Browser-based multiplayer IDEs**: Open implementations of shared Monaco or CodeMirror editors with presence and cursors.

- **Terminal sharing**: Tools like tmate or similar for collaborative terminal sessions as a lightweight pairing complement.

- Self-hosted combinations of Hopp-style screen sharing + Open Collaboration Tools for IDE-level co-editing.



**Frameworks for building custom systems**:  

The strongest open-source starting points are **Hopp** for high-quality developer screen sharing and remote control, and **Open Collaboration Tools** or CRDT-based editors (**realmeet**, **PairPad**, Yjs-powered projects) for true co-editing inside the IDE or browser.  

These can be combined with WebRTC audio/video and self-hosted infrastructure for a fully private pairing stack.  

Commercial tools (Tuple, CodeTogether, Live Share, Replit, etc.) provide polished UX, cross-platform reliability, and lower friction for most teams.  

Many engineering organizations use Live Share or CodeTogether for IDE-native collaboration and Tuple/Hopp-style tools when high-fidelity screen sharing and remote control are required.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Remote pair programming tools involve screen sharing, remote control, and sometimes shared access to source code and terminals. Proper access controls, encryption, and session hygiene are important.

- Open-source pairing tools offer transparency and self-hosting freedom but may require more setup and operational care than managed commercial products. Evaluate latency, security, and team workflow fit carefully.



---



**Made for remote engineering teams, pair-programming advocates, educators, and developers who believe great code is written together.**  

Let's make high-quality remote pairing accessible through both excellent commercial tools and strong open-source alternatives.
