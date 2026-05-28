# Fact or Cap 🎯

A multiplayer fact-checking game built on GenLayer where AI validators browse the web and decide who's right.

## Live Demo

[fact-or-cap.vercel.app](https://fact-or-cap.vercel.app)

## How It Works

1. Host creates a room and invites friends
2. Each round, one player submits a claim
3. Everyone else votes FACT or CAP
4. The claimer hits "Ask AI for Verdict"
5. GenLayer's AI validators independently browse the web, reason through the claim, and vote
6. Majority wins — verdict is final and stored onchain

Every action is a blockchain transaction. Room creation, votes, AI verdicts, XP distribution — all onchain on GenLayer Studionet.

## Screenshot

![Fact or Cap gameplay](screenshot.png)

## Tech Stack

- **Smart Contract:** Python Intelligent Contract on GenLayer
- **Frontend:** Vanilla JS, HTML, CSS — single file
- **Blockchain:** GenLayer Studionet
- **Frontend Hosting:** Vercel
- **Wallet:** MetaMask

## GenLayer Concepts Used

- **Intelligent Contracts** — Python contract calls `gl.nondet.exec_prompt()` to fact-check claims using AI
- **Optimistic Democracy** — multiple independent validators each check the claim and vote
- **Equivalence Principle** — validators don't need identical answers, just equivalent ones

## Contract
Address: 0xdE5528B07803BC7fEddD2c7AB6FE0F6Af84f0784



