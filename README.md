# WhatsApp Bot Project

This is a Node.js-based WhatsApp bot.

## Features

- Automated responses
- QR Code authentication
- Postgres database integration

## Prerequisites

- Node.js (v20 or newer)
- PostgreSQL database

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Fill in your database credentials and other settings

   ```bash
   cp .env.example .env
   ```

## Running the Bot

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Scan the QR Code:
   - The bot will generate a QR code in the terminal (or console logs).
   - Open WhatsApp on your phone.
   - Go to Linked Devices > Link a Device.
   - Scan the QR code displayed in the terminal.

3. Once connected, the bot will start listening for messages.

## Build for Production

To build and run in production mode:

```bash
npm run build
npm start
```

## Project Structure

- `server/`: Backend logic and bot controller
- `shared/`: Shared schemas and types
- `client/`: Frontend dashboard (if applicable)

## License

MIT
