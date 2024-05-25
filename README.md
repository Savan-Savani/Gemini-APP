
# Gemini App

A basic React.js application for learning AI API integration using the Google Generative AI SDK. This project demonstrates how to use the Google Generative AI API in a React application.

## Live Demo

You can view the live demo of the application [here](https://gemini-app-zeta.vercel.app/).

## Features

- Integrates with Google Generative AI API
- Simple chat interface
- Demonstrates basic API integration and usage

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Node.js (>= 14.x)
- npm (>= 6.x) or yarn

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/gemini.git
   cd gemini
   ```

2. Install the dependencies:

   ```sh
   npm install
   # or
   yarn install
   ```

### Setup Environment Variables

Create a `.env` file in the root of the project and add your Google Generative AI API key:

```env
VITE_GOOGLE_GEMINI_API_KEY=your_api_key_here
```

### Running the Application

To run the application in development mode, use:

```sh
npm run dev
# or
yarn dev
```

### Building for Production

To build the application for production, use:

```sh
npm run build
# or
yarn build
```

### Previewing the Production Build

To preview the production build locally, use:

```sh
npm run preview
# or
yarn preview
```

## Deployment

The application is deployed on Vercel. To deploy your own version, follow these steps:

1. Push your code to a GitHub repository.
2. Link the repository to your Vercel project.
3. Set up the environment variable `VITE_GOOGLE_GEMINI_API_KEY` in the Vercel dashboard.

## Dependencies

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Google Generative AI SDK](https://ai.google.dev/gemini-api/docs/get-started/node) - SDK for interacting with Google Generative AI

## DevDependencies

- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [ESLint](https://eslint.org/) - Find and fix problems in your JavaScript code
- [@vitejs/plugin-react](https://www.npmjs.com/package/@vitejs/plugin-react) - Official Vite plugin to enable React fast refresh

