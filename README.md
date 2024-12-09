# FRAPPS: Fractal Apps

Frapps is a modular, open-source toolkit for building and implementing fractal apps on Ethereum (or other EVM-based blockchain networks).

Fractal apps enable communities to make collective decisions through [fractal democracy](https://optimystics.io/fractal-democracy) - an innovative framework that scales human coordination while fostering genuine engagement. At its foundation lies the [Respect Game](https://optimystics.io/respectgame), where participants earn reputation (called [Respect](https://optimystics.io/respect)) through peer evaluation of their contributions. This reputation then enables sophisticated governance processes, from council formation to resource allocation.

For a complete understanding of how these tools transform community coordination, we encourage you to explore the [Optimystics Toolkit](http://optimystics.io/tools). There you'll find in-depth documentation of how frapps enables:

- Democratic coordination through fractal processes
- Verifiable on-chain reputation building
- Enhanced community collaboration and networking
- Sophisticated governance frameworks
- Resource allocation through peer evaluation
- Meaningful relationship building
- Enjoyable social experiences
- Knowledge sharing and collective learning

## Core Implementations

Our software spans three main implementations, each bringing unique capabilities while remaining composable. From lightweight consensus tools to sophisticated governance frameworks, these systems work together to enable better collective decision-making.

While originally developed across multiple repositories, this consolidation provides a clear overview of our modular infrastructure that enables communities to coordinate effectively at any scale. Active development often appears first in developers' personal repositories before being merged into the Optimystics organization. Links to both are provided to ensure access to the latest updates.

Below you'll find an overview of each implementation, including links to all relevant repository versions. We've also curated articles with video demonstrations and detailed documentation to help understand how each implementation works.

### 1. ORDAO/Fractalgram Implementation

**EVM Infrastructure:** ORDAO provides advanced governance infrastructure built around the Optimistic Respect-based Executive Contract (OREC), enabling truly decentralized on-chain execution of community decisions through an innovative consent-based voting system. Under consistent active development for over 8 months, this implementation was [approved](https://snapshot.org/#/optimismfractal.eth/proposal/0x3c35f474b1e2c037f32455abd75d027aa29d402200ac649fecb8b46c789c26a3) by the Optimism Fractal [Council](http://optimismfractal.com/council) to become the new version of Optimism Fractal smart contracts and is in the process of being integrated with the Fractalgram web app.

- EVM Repositories (work split across both as developer transitions to new structure):
    - Optimystics Organization: [ORDAO Repository](https://github.com/Optimystics/ordao) | [Original frapps repository](https://github.com/Optimystics/frapps)
    - Original Development: [ORDAO (dev repo)](https://github.com/sim31/ordao) | [frapps (dev repo)](https://github.com/sim31/frapps)
- Learn more: [ORDAO article](https://optimystics.io/ordao) | [OREC article](https://optimystics.io/orec)

**Front-End:** The Fractalgram web app provides a seamless interface for live community events, enabling real-time consensus building, engaging gameplay, and onchain submission. This modern implementation enhances the user experience with an intuitive interface while maintaining deep integration with the ORDAO smart contracts.

- Optimystics Organization: [Fractalgram-Web](https://github.com/Optimystics/fractalgram-v2-respect-game-front-end)
- Original Development: [Fractalgram-Web (dev repo)](https://github.com/fatherabraham-hms/fractalgram)
- Try the app at: [respect-game.vercel.app](http://respect-game.vercel.apphttps://respect-game.vercel.app/login)
- Learn more: [Fractalgram article](https://optimystics.io/fractalgram)

### 2. Respect.Games App

A full-featured application enabling asynchronous gameplay, on-chain contribution tracking, and flexible reward distribution. The [Respect.Games](http://Respect.Games) platform provides an all-in-one solution for launching and managing Respect Games, complete with user profiles and integrated onchain proposal voting. 

This implementation focuses on making the Respect Game accessible to a broader range of communities with different needs. Enhanced by Graph Protocol integration for efficient data querying, it offers a comprehensive interface for asynchronous community coordination. Developed over 2-3 months of full-time work and completed in September 2024, tCurrently in testing phase with multiple communities. 

**EVM Infrastructure:**

- Optimystics Organization: [Respect.Games Contracts](https://github.com/Optimystics/Respect.Games-app-smart-contracts)
- Original Development: [Respect.Games Contracts (dev repo)](https://github.com/n0umen0n/RGRG)

**Front-End:**  

- Optimystics Organization: [Respect.Games-Frontend](https://github.com/Optimystics/respect.games-ui) | [Respect.Games-Frontend (dev repo)](https://github.com/lennarlehestik/respectgameui)
- Graph Integration: [Respect.Games-graph](https://github.com/Optimystics/respect.games-graph) | [Respect.Games-graph (dev repo)](https://github.com/lennarlehestik/respectgamegraph)

- Try the app at [Respect.Games](http://Respect.Games) and explore more in the [Respect.Games article](https://optimystics.io/respect-games-app).

### 3. Original Optimism Fractal Software

Our first generation software provides basic infrastructure for playing the Respect Game on OP Mainnet, enabling consensus submission and Respect token distribution according to the Fibonacci ratio during all weekly Optimism Fractal events. Initially deployed in October 2023, it was in continuous use for over a year with recent commits adding functionality. 

The original implementation uses a Fractalgram Telegram client for coordinating live consensus games, paired with a basic web interface for submitting consensus results on-chain. These tools have successfully enabled weekly Optimism Fractal events since launch.

- [EVM Infrastructure Repo](https://github.com/Optimystics/op-fractal-sc)
- Frontend Repositories: [Fractalgram-Telegram-Client](https://github.com/Optimystics/fractalgram) | [OPF-Web-Interface](https://github.com/Optimystics/op-fractal-frontend)
- Learn more: [Documentation & Demo](https://optimystics.io/first-generation-opf-software)

## Additional Infrastructure

Our repositories also include Firmament, which is a currently inactive project that was significantly developed for many months to enable fractal communities to facilitate independent computing using Git and IPFS. You can explore two related repositories our Github organization and learn more  in the [Firmament article](http://optimystics.io/firmament).

While this repository focuses on our EVM implementations, we've also developed complementary infrastructure on Antelope networks demonstrating the versatility of these coordination systems. You can learn more about these implementations in this [repository](https://github.com/Optimystics/eden-fractal-contract), the [original repo](https://github.com/James-Mart/eden-fractal-contract), and this [article](https://edencreators.com/tools). 

## Get Involved

All code is open-source under MIT/GPL-3.0 licenses. All our tools and documentation are under community-driven development. Here are some ways to get involved:

- Explore the [Optimystics Toolkit](http://optimystics.io/tools) to learn more about all of our tools
- Join our [weekly events](http://lu.ma/optimystics) to meet developers and experience these tools firsthand
- Explore the [Development Hub](https://optimystics.io/optimism-fractal-development-hub) to find ongoing projects where you can contribute
- Connect through our [communication channels](https://optimystics.io/contact) and feel free to ask questions
- Watch implementation videos in our [video library](https://optimystics.io/contact) to see the tools in action

While organized by implementation above, these components are designed for modularity and composability. We welcome contributions and adaptations that help communities thrive through better coordination.
