# pos

Fixed address for a private, password-protected app that runs on its owner's laptop.

`index.html` forwards to the laptop's current Cloudflare tunnel address, stored in `tunnel.json`. The laptop updates `tunnel.json` automatically whenever the tunnel restarts. No personal data is stored here.
