## whoami

Backend engineer who leans toward systems programming and Ai Systems. I build distributed backends in **Rust**, ship on-chain programs on **Solana**, and wire everything together with modern web tooling. I like working close to the metal — async pipelines, message queues, encrypted delivery, and custodial wallet infrastructure.

---

## What I'm building

**Gridrock** - [GridRock.git](https://github.com/its-YogeshChandra/GridRock.git)
A distributed key-value store built from scratch in Rust. 

**StreamWeaver** — [StreamweaverV2](https://github.com/its-YogeshChandra/StreamweaverV2)  
Context-aware encrypted video delivery as an API. Upload an MP4, get back an AES-128 encrypted HLS stream, AI-generated chapters, seek-bar thumbnails, and a full transcript. Rust gateway → Redis queue → async worker → S3 CDN. Zero FFmpeg or crypto code on the client side.

**Redshift** — [Redshift](https://github.com/its-YogeshChandra/Redshift)  
Solana custodial payment pipeline with on-chain multisig. Orders queue in Redis, a Rust async worker executes create → approve (×5 owners) → treasury transfer on-chain via Anchor. Monitored by a real-time terminal dashboard built in Ratatui.

---

## Recent Work

**Amipay** — https://amypay.fun  
Conversational USDC remittance on Solana. Say "Send $100 to Mom" — DeepSeek AI parses the intent, a Rust backend validates and orchestrates, an Anchor smart contract settles on-chain. React Native mobile app, custodial wallets, no blockchain knowledge required from the user.

---

## Stack

Rust · Solana · Anchor · Actix-Web · Tokio · PostgreSQL · Redis · React Native · Next.js · TypeScript · Docker · FFmpeg
