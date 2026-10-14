# AI-Local-DLP-Enterprise

![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Available-brightgreen)

## Description

AI-Local-DLP-Enterprise is a browser extension that monitors and alerts on sensitive data usage with AI agents. The extension integrates with SIEMs, webhooks, and chat platforms to provide visibility into AI interactions without blocking user actions—users maintain full control over whether to send data, but receive alerts about data types being used.

The project enables organizations to track sensitive data exposure through AI tools, logging sender identity, department, timestamp, file information, and AI agent usage to pre-configured security environments.

## Features

- **Data Classification Monitoring** — Real-time detection of sensitive data usage with AI agents
- **User-Controlled Sharing** — Users decide whether to send data while being informed of data types
- **SIEM & Webhook Integration** — Sends alerts to enterprise security infrastructure
- **Comprehensive Logging** — Records sender, department, timestamp, file name, and AI agent used
- **Multi-Platform Chat Support** — Works with various chat and AI platforms
- **Enterprise-Ready** — Designed for organizational compliance and monitoring

## Tech Stack

- **Browser Extension** — Chrome/Chromium-based
- **Frontend** — HTML, CSS, JavaScript (extension UI)
- **Integration** — Webhooks, SIEM APIs
- **Runtime** — Chrome Web Store

## Prerequisites

- Chrome or Chromium-based browser (v90+)
- Administrator access for deployment (enterprise environments)
- Pre-configured webhook endpoint or SIEM integration

## Getting Started

### Installation from Chrome Web Store

1. Visit the [AI-Local-DLP extension on Chrome Web Store](https://chromewebstore.google.com/detail/ai-local-dlp/cpgcgdlnjhjnblnigkgaelmaplcgpfpd)
2. Click **Add to Chrome**
3. Confirm permissions when prompted

2. Load the extension in Chrome:
   - Open `chrome://extensions/`
   - Enable **Developer mode** (top-right toggle)
   - Click **Load unpacked**
   - Select the project directory

## Usage

1. **Configuration** — Set up webhook endpoints and SIEM integration in extension settings
2. **Monitoring** — The extension automatically detects sensitive data interactions with AI agents
3. **Alerts** — When sensitive data usage is detected, an alert notifies the user
4. **User Action** — User decides whether to proceed; if sent, the action is logged to configured endpoints
5. **Review** — Access logs and alerts through your SIEM or webhook receiver

## Environment Variables

Configuration is handled through the extension settings interface. The following should be configured:

| Variable | Description | Required |
|----------|-------------|----------|
| Webhook URL | HTTPS endpoint to receive alerts | Yes |
| SIEM Endpoint | API endpoint for SIEM integration | No |
| Department Field | Custom department identifier | Yes |
| API Key | Authentication for webhook/SIEM endpoints | Yes |

## Project Structure

```
AI-Local-DLP-Enterprise/
├── README.md                 # Project overview and documentation
└── Privacy.md               # Privacy policy and data handling
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Please ensure your code follows the project's coding standards and includes appropriate documentation.

## License

This project is not currently under a specified license. See the repository for more details.

---

**Chrome Web Store:** [AI-Local-DLP Extension](https://chromewebstore.google.com/detail/ai-local-dlp/cpgcgdlnjhjnblnigkgaelmaplcgpfpd?authuser=0&hl=pt-BR)

---

<p align="center">
  <a href="https://readmebot.dev?utm_source=readme_badge&utm_medium=github">
    <img src="https://readmebot.dev/badge.svg" alt="Docs by ReadmeBot" height="20">
  </a>
</p>
