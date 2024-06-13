# ZeroDev Fullstack Starterkit 🚀

Welcome to the ZeroDev Fullstack Starterkit! This starter kit is designed to help you quickly set up and start building a full-stack decentralized application (dApp) using ERC-4337 smart accounts. Below is an overview of the stack and instructions on how to get started.

## Tech Stack 🛠️

- **NextJS**: A React framework for building server-side rendered (SSR) and static web applications.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Shadcn UI**: Pre-built UI components for faster development.
- **Drizzle ORM**: TypeScript ORM for managing database operations.
- **Vercel Postgres**: Vercel's managed PostgreSQL database service.
- **Lucia**: Lightweight and flexible authentication library.
- **Stripe**: Payment processing for handling transactions.
- **Resend**: Email API for sending transactional emails.

## Getting Started 🏁

## Prerequisites 📋

- Node.js (>= 14.x)
- Yarn or npm
- PostgreSQL

## Next Steps ⚙️

1.  Add Environment Variables to your .env
2.  `pnpm run db:generate`
3.  `pnpm run db:migrate`
4.  `pnpm run dev`
5.  Open http://localhost:3000 in your browser
6.  `pnpm run stripe` listen in a separate terminal

## Building for Production 📦

```bash
yarn build
```

## Deployment 🚢

The starter kit is optimized for deployment on Vercel. Follow the Vercel deployment guide to deploy your application.

Project Structure 🗂️

```bash
/
├── components/ # UI components
├── pages/ # Next.js pages
├── styles/ # Tailwind CSS styles
├── utils/ # Utility functions
├── drizzle/ # Database models and migrations
├── public/ # Public assets
├── .env.local # Environment variables
├── package.json # Project dependencies and scripts
└── README.md # Project documentation
```

## Available Scripts 📜

dev: Starts the development server.
build: Builds the application for production.
start: Starts the production server.
drizzle:migrate: Runs database migrations.
lint: Runs ESLint to check for code quality issues.

## Contributing 🤝

We welcome contributions! Please see our contributing guidelines for more details.

## License 📄

This project is licensed under the MIT License. See the LICENSE file for more information.

## Contact 📧

For questions or support, please open an issue in the repository or contact us at hello@vizieros.co

Happy coding! 🎉
