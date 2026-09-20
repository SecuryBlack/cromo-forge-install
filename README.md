# CromoForge Install Worker

Official Cloudflare Worker that dynamically serves the installation script for **CromoForge** based on the client User-Agent and operating system:

- **Linux / macOS:** `curl -fsSL https://install.cromoforge.dev | sudo bash`
- **Windows (PowerShell):** `irm https://install.cromoforge.dev | iex`

## License

Apache-2.0 License.
