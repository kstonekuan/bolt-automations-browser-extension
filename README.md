# <img src="public/assets/icon-128.png" alt="Bolt Automations Logo" width="32" align="center" /> Bolt Automations by Squash

## 💰 Save Tokens, 🚀 Save Time. Ship faster with bolt.

<div align="center">
  <img src="public/assets/black_circle_360x360.png" alt="Powered by Bolt.new - Made in Bolt Hackathon" width="150" />
  
  🏆 Built with Bolt for Bolt as part of the [World's Largest Hackathon presented by Bolt](https://hackathon.dev/)
</div>

Stop burning through tokens and missing important updates. This Chrome extension automatically manages your bolt.new workflow to dramatically reduce token usage and keep you informed of every task completion, error, or required input.

### How it saves your tokens
- **Auto Discussion Mode**: Automatically switches bolt to discussion mode after each task completion
- **Why this matters**: Discussion Mode uses approximately 90% fewer tokens than Build Mode (according to [bolt.new official docs](https://support.bolt.new/best-practices/maximizing-token-efficiency))
- **Result**: Massive token savings - discussion mode helps bolt think and plan its next steps without going off the rails

### How it saves your time  
- **Never Miss a Beat**: Real-time Discord notifications when tasks complete, errors occur, or input is needed
- **Read Less, Decide Faster**: Optional AI-powered summaries give you the essential information without wading through verbose outputs
- **Stay in Flow**: No more tab-switching or constant checking - get notified and stay focused on what matters

## Key Features

- ✅ **Smart Token Management**: Auto-enables discussion mode after task completion
- 🔔 **Instant Discord Notifications**: Know immediately when bolt needs your attention
- 🤖 **AI-Powered Summaries**: Get concise updates with your choice of AI provider (optional)
- 🔒 **Privacy First**: All credentials stored locally, never sent to external servers
- ⚡ **Zero Config**: Works out of the box with just a Discord webhook

## Quick Start

### Official Installation
[Install from Chrome Web Store](https://chromewebstore.google.com/detail/fmigbfjaaleaddlpeihbbjgkcggccpnb)

### Install from GitHub Release
1. Download the latest release from [GitHub Releases](https://github.com/kstonekuan/bolt-automations-browser-extension/releases)
2. Unzip to a folder
3. Open `chrome://extensions` in Chrome
4. Enable **Developer mode**
5. Click **Load unpacked** and select the unzipped folder

### Setup (2 minutes):
   - Click the extension icon
   - Make sure "Auto-enable discuss mode" is on
   - (Optional) Add your Discord webhook URL for notifications
   - (Optional) Choose AI provider and add API key for AI summaries
   - Click "Save Settings"
   - You're done! 🎉

## How It Works

1. **You work normally** - Use bolt.new as you always do
2. **Extension monitors** - Detects when tasks complete, errors occur, or input is needed
3. **Smart actions trigger**:
   - Automatically switches to discussion mode (saves tokens)
   - Sends Discord notification (saves time)
   - Generates AI summary if configured (saves reading)
4. **You stay informed** - Get notified without tab-switching or manual checking

## Configuration

### Discord Webhook (Optional)
1. In Discord: Server Settings → Integrations → Webhooks → New Webhook
2. Copy the webhook URL
3. Paste in extension settings

### AI Provider & API Key (Optional)
Adds AI-powered summaries to notifications. Choose from:

- **Google Gemini (2.0 Flash Lite)**: Google's lightweight and efficient model with a **free tier** - [see pricing](https://ai.google.dev/gemini-api/docs/pricing)
- **Anthropic (Claude 3 Haiku)**: Fast and cost-effective Claude model
- **OpenAI (GPT-4o Mini)**: OpenAI's optimized small model

Without an API key: You get bolt's raw message  
With an API key: You get concise, actionable summaries

## Troubleshooting

**No notifications?**
- Check Discord webhook URL is correct (use "Test Notification" button)
- Ensure you're on bolt.new
- Refresh the page after installing

**AI summaries not working?**
- Verify your API key is correct for the selected provider
- Check that you have available credits/quota
- Ensure you've selected the correct AI provider in settings
- Check browser console for errors

## Installation

### Option 1: Install from Release (Easiest)
1. Download the latest `bolt-automations-vX.X.X.zip` from [Releases](https://github.com/kstonekuan/bolt-automations-browser-extension/releases)
2. Unzip the file to a folder on your computer
3. Open Chrome and go to `chrome://extensions`
4. Enable **Developer mode** (toggle in top right)
5. Click **Load unpacked**
6. Select the folder where you unzipped the extension
7. You're ready to go! 🎉

### Option 2: Build from Source
1. Clone the repository:
   ```bash
   git clone https://github.com/kstonekuan/bolt-automations-browser-extension.git
   cd bolt-automations-browser-extension
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the extension:
   ```bash
   npm run build
   ```

4. Load the extension in Chrome:
   - Open `chrome://extensions`
   - Enable **Developer mode**
   - Click **Load unpacked**
   - Select the `dist` folder

For detailed development information, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Privacy & Security

- 🔒 All credentials stored locally
- 📡 Only communicates with your configured services
- 🌐 Only active on bolt.new
- 🔐 All traffic encrypted (HTTPS)

## License

MIT License - see [LICENSE](LICENSE)

## Support

Visit [Squash](https://www.trysquash.dev/) or [open an issue](https://github.com/kstonekuan/bolt-automations-browser-extension/issues)