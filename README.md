# Message App

## Project Overview

This project is a simple Svelte application where you can enter a message, and it will automatically display what you wrote. The application consists of three main parts: a header, a main section, and a footer.

## Features

- **Header**: Contains the title of the application.
- **Main Section**: Includes a text input where you can type your message and a div that displays the entered message in real-time.
- **Footer**: Displays additional information or links.

## How It Works

1. **Enter a Message**: Type your message into the text input field in the main section.
2. **Real-Time Display**: As you type, the message is displayed in a div below the input field.
3. **Header and Footer**: The header and footer provide context and additional information for the application.

# Installation and development

## sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.