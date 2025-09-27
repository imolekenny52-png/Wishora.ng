# Wishora MVP (Gadgets-only public donation marketplace)

## Overview
Minimal MVP to run Wishora locally in GitHub Codespaces / any Node environment.
- Backend: Express (server)
- Frontend: React (client)
- Storage: simple JSON file (db.json) for prototypes
- Uploads saved to `server/uploads/`

**This is a prototype** — payment & BVN integrations are stubbed. Replace placeholders before handling real money or PII.

## Quick start (GitHub Codespaces)
1. Open this repo in GitHub Codespaces.
2. Open a terminal in the Codespace root.
3. Install server and client:
   ```bash
   cd server
   npm install
   cd ../client
   npm install
