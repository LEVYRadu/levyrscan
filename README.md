# LEVYRscan

**LEVYRscan** is the on-chain verification module for LEVYR — a protocol for real-time zoning and development feasibility.

This lightweight web app allows users to verify the authenticity of LEVYR-generated feasibility reports by searching for their corresponding hash or transaction ID. All hashes are anchored on-chain and stored with a logic version, timestamp, and context.

## Features

- Search by report hash or transaction hash
- View context (`report` or `pro_account`)
- Display timestamp and logic version
- Link to Etherscan for public proof
- Designed to be embedded via iframe on [levyr.ca/scan](https://levyr.ca/scan)

## Status

This is a live MVP project currently being integrated into LEVYR's core stack. UI will be styled once final branding assets (logo, font, etc.) are added.

## Tech Stack

- HTML/CSS/JS (or React if upgraded)
- Deployed on Vercel
- Reads data from:
  - LEVYR smart contract on Sepolia
  - Supabase (for metadata like logic version)

## Philosophy

Built for clarity, speed, and trust. Nothing flashy — just verifiable proof.

---

More coming soon.
