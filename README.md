# Crypto QR Wizard

![Crypto QR Wizard](https://sjc.microlink.io/z74_KA396HkdLPsvi-cDEqQzkzuo3x6CgIyi0lPcwV_d9EE93TnbA9Lc6NTMTGacpI-PzJQbmMFojduwk6mJdg.jpeg)

## Live Demo

*[Try Crypto QR Wizard Live](https://kzmkgbo1j40s6rtyjy9y.lite.vusercontent.net)*

> *⚠ IMPORTANT DISCLAIMER:* The live demo is a frontend-only version. The AI function that powers natural language processing requires a server running the Flock Web3 Agent Model, which is not included in this deployment. A full demonstration with working AI functionality can be seen in the demo below and will be demonstrated during Demo Day. In the meantime, you can explore the UI and test the manual function execution in the Debug panel.

## Pitch & Demo Video


*[Crypto QR Wizard Pitch Demo - YouTube](https://www.youtube.com/watch?v=fauX_Gng3fU)*


## Overview

Crypto QR Wizard transforms complex cryptocurrency transactions into user-friendly QR codes through natural language processing. Users simply describe what they want ("Send 0.05 ETH to this address with a blue theme"), and our application leverages the Flock Web3 Agent Model to generate customized, transaction-ready QR codes that work with popular crypto wallets.

## Features

- *Natural Language Processing*: Describe your transaction in plain English
- *Multi-Chain Support*: Works with Ethereum, Bitcoin, Polygon, Solana, and more
- *Customizable QR Codes*: Personalize with colors, logos, titles, and messages
- *Standards Compliance*: Generates QR codes compatible with major wallet apps (EIP-681, BIP-21, etc.)
- *Debug Tools*: Advanced tools for developers to test and explore functionality
- *Responsive Design*: Works on desktop and mobile devices

## How It Works

1. *Natural Language Input*: Users describe their transaction in plain English
2. *AI Parsing*: Flock Web3 Agent interprets the request, extracting transaction details and customization preferences
3. *QR Generation*: The system generates a standards-compliant QR code
4. *Customization*: Users can further personalize their QR code with colors, logos, and text

## The Flock AI Advantage

The Flock Web3 Agent Model is the core innovation that makes Crypto QR Wizard possible:

- *Specialized Web3 Knowledge*: Unlike general-purpose AI models, Flock understands blockchain-specific concepts, addresses, and protocols
- *Function Calling*: Flock can intelligently select and call the appropriate functions for different blockchain networks
- *Customization Intelligence*: The model extracts styling preferences from natural language and suggests appropriate themes based on transaction type
- *Multi-Chain Support*: Works across multiple blockchains with specialized parsing for each

## Technologies Used

- *Frontend*: Next.js, React, Tailwind CSS, shadcn/ui
- *QR Code Generation*: qr-code-styling library
- *AI*: Flock Web3 Agent Model (via local proxy)
- *State Management*: React Context API

## Getting Started

### Prerequisites

- Node.js 18+
- Access to Flock Web3 Agent Model (for full functionality)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/crypto-qr-wizard.git
   cd crypto-qr-wizard
