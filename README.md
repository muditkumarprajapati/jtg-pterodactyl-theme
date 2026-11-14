# JTG Theme for Pterodactyl Panel

A sleek, void-black, glassmorphic theme inspired by **JTG Panel** for **Pterodactyl Panel**.

## Features
- **Matching Auth Screens**: Custom styled Login, Register, and Password Reset screens with glassmorphic cards and Outfit typography.
- **Consistent Inside Dashboard**: Void-black (`#030305`) canvas, sleek `#0a0a0d` server cards, Chakra Petch headings, and JetBrains Mono console.
- **100% Blueprint Compatible**: Retains all Blueprint markers and automatically rebuilds Blueprint extensions so all other extensions continue to work seamlessly.
- **Pure Script-Based**: No `.blueprint` wrapper needed for this theme; install, update, and remove via an automated bash script.

## Quick Installation on VPS

Run this single command as root:

```bash
curl -sSL https://raw.githubusercontent.com/muditkumarprajapati/jtg-pterodactyl-theme/main/install.sh | tr -d '\r' | bash
```

### Menu Options
1. **Install JTG Theme**: Deploys the theme assets, updates the wrapper template, and optimizes cache/extensions.
2. **Update JTG Theme**: Refreshes theme assets and rebuilds caches.
3. **Remove JTG Theme**: Restores default Pterodactyl panel cleanly.
4. **Exit**.
