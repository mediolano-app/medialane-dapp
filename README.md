# IP Marketplace for the Integrity Web

Medialane is a permissionless marketplace where creators, autonomous agents, and businesses own, license, and trade intellectual property with full transparency, control, and sovereignty.
Built on the Mediolano Protocol, MediaLane transforms digital assets into programmable public goods — empowering a new era of content creation and monetization.

<img width="1342" height="661" alt="image" src="https://github.com/user-attachments/assets/7a2eb035-9a27-43f9-8c18-73a4fc9bda7b" />


Mediolano Protocol empowers creators to register, license and monetize intellectual property. Powered on Starknet.

Quick links:
<br>
<a href="https://ip.mediolano.app">Mediolano Dapp</a>
<br>
<a href="https://mediolano.xyz">Website mediolano.xyz</a>
<br>
<a href="https://t.me/MediolanoStarknet">Telegram</a>
<br>
<a href="https://discord.gg/NhqdTvyA">Discord</a>
<br>
<a href="https://x.com/mediolanoapp">X / Twitter</a>
<br>

> [!IMPORTANT]
> Medialane dapp is in constant development and the current version runs on Starknet's Sepolia devnet. Use for testing purposes only. 

## Getting Started

## Running locally

Dapp requirements:
- Next.js 15
- React 19
- Node.js 18.18 or later.
- macOS, Windows (including WSL), and Linux are supported.

Clone the repository to your local machine:

```bash
git clone https://github.com/mediolano-app/medialane-app.git
```
Install dependencies for Next.js 15 + React 19:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Running via Docker

To run the containerized application, there is no dependencies requirement. 

Clone the repository, and run:

```bash
 docker build -t medialane-app .     
```

To build the image. Then, start the container:

```bash
docker run -p 8080:8080 medialane-app
```
