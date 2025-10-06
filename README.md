# AI Component Builder
An innovative web application that leverages the power of the Google Gemini API to generate React components with Tailwind CSS styling directly from user prompts. Built with React, Vite, and Tailwind CSS for a modern, fast, and responsive user experience.

# Introduction
This project is an AI-powered tool designed to streamline the front-end development workflow. Instead of writing boilerplate component code manually, developers can simply describe the component they need in plain English. The application sends this prompt to the Gemini API and renders the generated JSX code, complete with functional logic and Tailwind CSS classes, directly in the browser.

# Features
AI-Powered Component Generation: Describe UI elements, components, or even entire layouts in natural language.

Real-time Code Preview: Instantly see the generated React component rendered on the screen.

Syntax Highlighting: View the generated JSX code with proper syntax highlighting for readability.

Copy to Clipboard: Easily copy the generated code with a single click to use in your projects.

Responsive Design: A clean, modern UI built with Tailwind CSS that works beautifully on all devices.

Fast & Efficient: Built on top of Vite for a lightning-fast development experience and hot module replacement.

# Tech Stack
Frontend: React.js

Build Tool: Vite

Styling: Tailwind CSS

AI Model: Google Gemini API

Syntax Highlighting: react-syntax-highlighter (or similar)

# Getting Started
Follow these instructions to get a local copy up and running for development and testing purposes.

Prerequisites
You need to have Node.js and npm (or yarn/pnpm) installed on your machine.

Node.js (v18.x or later recommended)

npm

Installation
Clone the repository:

git clone [https://github.com/your-username/ai-component-generator.git](https://github.com/your-username/ai-component-generator.git)
cd ai-component-generator

Install NPM packages:

npm install

Set up environment variables:
Create a new file named .env in the root of your project directory and add your Google Gemini API key.

VITE_GEMINI_API_KEY="YOUR_API_KEY_HERE"

You can get your API key from the Google AI Studio.

Run the development server:

npm run dev

The application should now be running on http://localhost:5173 (or another port if 5173 is busy).
