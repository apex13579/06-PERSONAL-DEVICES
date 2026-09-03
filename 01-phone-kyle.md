* **Termux**
  * Operates in an isolated local command-line environment with storage permissions strictly scoped to its working directory.
* **Discord**
  * Sandboxed to prevent cross-app tracking, utilizing standard background connection handling for chat sync.
* **Brave**
  * Acts as your primary browser with native ad-blocking, tracker-stripping, and anti-fingerprinting configurations active.
* **Telegram**
  * Configured with background polling restricted to prevent continuous system tracking when the app is closed.
* **Immich**
  * Direct, encrypted background media backup syncing straight to your home lab storage.
* **Nextcloud**
  * Direct synchronization for files, bypassing third-party cloud intermediaries.
  * **Calendar**
    * Localized CalDAV sync routing directly through your Nextcloud instance.
* **Oura Ring**
  * Companion app isolated with Bluetooth permissions toggled to on-demand usage, preventing constant ambient beacon tracking.
* **Home Assistant**
  * **The new hub for your location data:** The Companion App's background location sensor securely pushes your device coordinates straight to your home lab via Tailscale, entirely removing third-party middlemen like Waze or Google Maps from your presence automation loop.
* **Waze**
  * Stripped of all background location duties. Location permission is locked strictly to *"Only while using the app,"* completely shutting down its ability to harvest or report your coordinates when you aren't actively looking at a route.
* **Shokz**
  * Direct Bluetooth audio device routing with zero data collection footprint.
* **Jellyfin**
  * Local media streaming client pulling directly from your home lab server library.
* **Tailscale**
  * Operates as your encrypted mesh VPN layer, securely tunneling your traffic back home for Home Assistant, Immich, and Nextcloud without exposing ports publicly.
* **Spotify**
  * Sandboxed media playback container isolated from unrelated device metrics.
* **AppFlowy**
  * Secure local and self-hosted workspace syncing.
* **Banking Apps**
  * **Banking Apps & Venmo:** Full account management, transfers, and security logins function normally.
  * **Digital Wallet:** Retains native Google Wallet functionality for store checkout counters, enabling wallet-free NFC tap-to-pay using your stock device configuration.
* **Work Folder**
  * Isolated entirely inside an independent Android Work Profile (via native settings or Shelter).
  * **Teams, Outlook, Authenticator, Monday, Duo, Zoom:** Confined strictly within the corporate work boundary, keeping their enterprise telemetry completely partitioned from your personal files, location sensors, and contacts.
* **Thunderbird Mail**
  * Direct IMAP/SMTP mail synchronization straight to your self-hosted mail server.
* **Wallet Folder**
  * **Digital Wallet:** Retains NFC hardware tokenization for physical store terminals, allowing you to leave physical cards at home while keeping standard stock security intact.
* **Stock Tracker App**
  * Isolated financial market data feed stripped of personal identifier hooks.
* **My Fitness Pal**
  * Restricted from scraping device contacts, local storage files, or background telemetry.
* **LinkedIn**
  * Contained safely away from personal storage access and persistent location tracking.
* **Instagram**
  * Denied access to local device storage, persistent background tracking, and contact graphs.
* **YouTube**
  * Wrapped inside a private browser tab or alternative client frontend to starve it of cross-site tracking cookies and profiling.
