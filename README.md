## Setup

1. **Create or use a secondary GitHub account** (highly recommended)
2. Fork the repository to your account
3. Click the green **"Code"** button above
4. Go to the **"Codespaces"** tab
5. Click **"Create codespace on main"**
6. Wait for the setup to complete (usually 2-5 minutes)

## How to Use

1. **Wait for Codespace initialization** - The setup process takes a few minutes. All dependencies and configurations will be installed automatically.

2. **Get your VLESS link** - Once ready, your VLESS proxy link will be printed directly in the terminal

   ![Terminal Screenshot](./docs/screenshot.png)

3. **Import the link** - Copy the generated VLESS link and import it into:
   - V2RayNG (Android)
   - Clash Meta
   - Or any other proxy application that supports VLESS

## Important Notes

### GitHub Codespaces Quota
- GitHub provides **120 free compute hours per month** (per core)
- For a 2-core Codespace: 120 ÷ 2 = 60 hours/month
- **Stop your Codespace when not in use** to preserve your hours
- You can always restart it later when needed

### Compatible Networks
Tested on Shecan (free plan). If these IPs work for you, the proxy should be functional:
- `63.141.252.203`
- `50.7.5.83`
- `94.130.50.12`

If these IPs don't work, try different datacenters or ISPs from your region.

### Troubleshooting
- If the Codespace fails to start, try creating a new one
- Check that your GitHub account has Codespaces enabled
- Ensure you have enough compute hours remaining for the month
- For network issues, try switching proxy protocols in your client app

## Disclaimer

This tool is provided for educational and legitimate use only. Users are responsible for complying with their local laws and regulations regarding proxy usage. The author is not responsible for any misuse or legal consequences arising from the use of this tool.

## License

This project is open-source. Please check the LICENSE file for details.
