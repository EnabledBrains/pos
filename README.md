# pos

Fixed address for a private, password-protected app that runs on its owner's laptop.

`index.html` forwards to the fixed address https://pos.dev-enabledbrains.workers.dev. That Cloudflare Worker reads the laptop's current tunnel address from `tunnel.json`, which the laptop updates automatically whenever the tunnel restarts. No personal data is stored here.
