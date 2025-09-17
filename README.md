# GotongChain Micro-crowdfunding + DAO 

📛 Project Name

GotongChain – Micro-Crowdfunding & DAO on Sui

🏆 Elevator Pitch (1–2 kalimat)

GotongChain adalah platform micro-crowdfunding berbasis blockchain Sui yang memungkinkan siapa pun berdonasi mulai dari nominal kecil. Dana disimpan dalam smart contract dan hanya bisa dicairkan ketika komunitas DAO menyetujui setiap milestone, memastikan transparansi dan kepercayaan.

🌱 Problem

Platform donasi tradisional kurang transparan; donor tak tahu kapan dan bagaimana dana dipakai.

Banyak proyek sosial butuh pendanaan cepat dengan tiket kecil (Rp10k–Rp20k) namun tetap aman.

💡 Solution

Semua proposal dan pencairan dana on-chain di Sui → transparan & tidak bisa dimanipulasi.

Sistem milestone voting: komunitas DAO memutuskan kapan dana dilepas.

Biaya transaksi rendah & kecepatan tinggi Sui → cocok untuk donasi mikro.

🛠 Tech Stack
Layer	Tool / Library
Blockchain	Sui (Move smart contract)
Smart Contract	Move modules: proposal, treasury, vote
Frontend	React / Next.js + @mysten/sui.js
Wallet	Ethos / Mysten Sui Wallet
Storage	IPFS / nft.storage untuk dokumen & bukti
Dev Tools	Sui CLI, Sui SDK, Typescript
🔑 Core Features (MVP)

Create Proposal – Creator submit deskripsi + target dana + daftar milestone (metadata ke IPFS).

Donate – User kirim SUI ke Treasury object (smart contract).

On-chain Voting – Donor & community vote untuk tiap milestone.

Milestone Release – Dana otomatis cair kalau quorum terpenuhi.

Transparency Dashboard – Semua transaksi & IPFS hash publik.

📱 UI / UX (Wireframe Singkat)

Home / Explore: daftar proyek + progress bar.

Project Detail: tombol Donate & Vote, milestone breakdown.

Submit Proposal: form untuk creator.

DAO Dashboard: daftar proposal, status voting, tombol Release Funds.

🚀 Roadmap

Hackathon MVP: core contract, simple React frontend, wallet connect, donate & vote.

Post-hackathon: multi-chain support, fiat on-ramp, reputasi verifikator.

👥 Team

Solo builder: [YourName] (seeking collaborators for frontend & Move dev).
