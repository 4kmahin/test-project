# Cursor

A Node.js project built with TypeScript and Next.js.

## Tech Stack

| Layer       | Technology  |
| ----------- | ----------- |
| Runtime     | Node.js     |
| Language    | TypeScript  |
| Framework   | Next.js     |

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm or yarn

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd cursor
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a local environment file:

   ```bash
   cp .env.example .env
   ```

   Update `.env` with your local configuration.

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Scripts

| Command       | Description              |
| ------------- | ------------------------ |
| `npm run dev` | Start development server |
| `npm run build` | Build for production   |
| `npm run start` | Start production server |
| `npm test`    | Run tests                |

## Environment Variables

This project uses [dotenv](https://github.com/motdotla/dotenv) for environment configuration. Define variables in a `.env` file at the project root.

## Project Structure

```
cursor/
├── cursor.md       # Project notes and resources
├── package.json
└── README.md
```

## Documentation

- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)
- [Node.js Documentation](https://nodejs.org/docs)

## License

ISC
