# Privacy Policy — Professor Oak

**Effective Date:** March 3, 2026

This Privacy Policy explains how **Professor Oak** (“the Bot”) collects, uses, and stores information when you interact with it on Discord.

## 1) What Professor Oak Does
Professor Oak is a companion bot to Pokétwo that provides Pokémon spawn naming and optional features that help users manage **Collections** and **Shiny Hunts**, including server-configurable ping behavior.

## 2) Information We Collect and Process

### A) Discord identifiers (stored)
Professor Oak stores Discord identifiers to associate settings with the correct user/server and to operate server features:
- User IDs
- Server (Guild) IDs
- Channel IDs (for certain server settings)
- Message IDs (for certain operational features, such as correlating spawn events and bot responses)

### B) Message content (processed; limited storage)
Professor Oak processes message content **in servers where it is installed**:
- **Pokétwo messages** (e.g., spawn/catch messages) to identify spawns and provide naming/pings.
- **User command messages** directed at Professor Oak (e.g., `!oak …`) to set or modify user preferences and server configuration.

**No Direct Messages:** Professor Oak does **not** provide DM-based features and does **not** intentionally process direct messages.

### C) Images (processed transiently)
Professor Oak temporarily downloads images associated with Pokétwo spawns for classification/naming. These images are used for immediate processing and are **not saved to disk** for long-term retention in production.

### D) User preference and server configuration data (stored in SQLite)
Professor Oak stores bot-operational data such as:
- Shiny Hunt selections
- Collection entries
- AFK preference toggles (whether you receive Shiny Hunt / Collection pings)
- Region/type preference toggles (if enabled)
- Catch ping settings (if enabled)
- Server configuration (e.g., role ping configuration, categories, feature options/flags, excluded channels)
- Reserved entries (associating a reserved target with a user ID; may include a stored username string where used for functionality)

### E) Diagnostics & operational logs (may be stored)
Professor Oak may store operational logs to improve reliability and performance. These logs may include:
- Error traces
- Basic performance metrics and timing information
- Records needed to correlate bot responses to events (e.g., message IDs/timestamps)

## 3) How We Use Information
We use collected/processed information to:
- Provide spawn naming and related features
- Store and apply user settings (Collections/Shiny Hunts and preference toggles)
- Store and apply server configuration (roles/categories/options)
- Prevent abuse, maintain security, diagnose issues, and improve reliability/performance

## 4) Data Retention and Deletion
**Retention policy:** retained **until deleted**.

- If a user clears their Collections or Shiny Hunt settings, the corresponding entries are deleted from the database and **are not recoverable** (no backup maintained for cleared Collections/Shiny Hunts).
- Server configuration data may be deleted when the Bot is removed from a server, or upon request by server administrators (where feasible).

## 5) Sharing and Disclosure
We do **not** sell, rent, or trade information.

We may disclose information only:
- As necessary to operate the Bot on its hosting infrastructure (hosted on a personal DigitalOcean server)
- If required by law or valid legal process
- To protect the security and integrity of the Bot and its users

## 6) Security
We take reasonable steps to protect stored data through access controls and operational safeguards. No system is perfectly secure.

## 7) Children’s Privacy / Age
Professor Oak is a general-audience utility bot and does not include age-specific features. Users must meet Discord’s minimum age requirements and comply with Discord’s policies.

## 8) Contact and Requests
To request deletion of stored data associated with your Discord user ID or to ask privacy questions, contact:

**Email:** profoakdev@outlook.com  
Include your Discord user ID and (if applicable) the relevant server (guild) ID to help locate records.

## 9) Changes
We may update this Privacy Policy from time to time. Updates will be reflected by updating the Effective Date above.
