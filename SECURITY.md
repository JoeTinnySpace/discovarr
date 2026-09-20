# Security & Privacy Policy

## Our Security & Privacy Model

Discovarr is designed with a **privacy-first, zero-knowledge** architecture. We believe privacy is an essential right, especially when managing self-hosted infrastructure.

### 1. Local Credential Storage
* All Radarr server URLs, Tailscale endpoints, and API Keys are stored exclusively on your device inside standard browser `localStorage`.
* Our cloud infrastructure does not maintain any user databases, persistent auth sessions, or logging of individual users' Radarr server targets.

### 2. Network Isolation
* Your Radarr server credentials are only invoked when you explicitly initiate an action (testing your connection, saving settings, or clicking a "Push" button in your watchlist).
* No background daemon, automated webhook, or scheduled scraper polls your local network.

### 3. Reporting Security Concerns
If you discover any security vulnerability or potential privacy leak in our network relay or client applications, please report it responsibly by contacting:

- Email: `brandezonline@gmail.com`
- Or open a private security advisory through GitHub.

We investigate all reports promptly and deploy fixes as high-priority releases.
