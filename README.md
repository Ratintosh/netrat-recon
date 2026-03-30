<img width="1280" height="200" alt="netrat-recon-banner" src="https://github.com/user-attachments/assets/b29d5623-3214-44e3-ac97-1c9917d09f6d" />

# NetRat Recon

**NetRat Recon** is a work-in-progress reconnaissance frontend tool for KOTHs and CTFs.

It aims to provide a simple desktop UI for organizing and visualizing recon tasks, built with Wails.

---
## Current Status

This project is **not yet functional**, and is still under active development.

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Go (latest recommended)  
- Node.js (LTS recommended)  
- Wails CLI  

Install Wails:
```bash
go install github.com/wailsapp/wails/v2/cmd/wails@latest
```

Clone the repo:
```bash
git clone https://github.com/Ratintosh/netrat-recon.git
cd netrat-recon
```

Install Dependencies:
```bash
cd frontend
npm install
cd ..
```

Run in Development Mode:
```bash
wails dev run
```
