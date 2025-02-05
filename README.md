# Next.js 15 App Router - Functional Component Rendering Issue in Pages Directory

This repository demonstrates a bug encountered when using functional components in the `pages` directory within a Next.js 15 App Router application. The application fails to render correctly. 

## Bug Description

When deploying a Next.js 15 application utilizing the App Router, a functional component placed within the `pages` directory does not render as expected. Instead of displaying the component's content, the application may show a blank screen or an error.

## Reproduction

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.
5. Observe the incorrect rendering behavior in the browser.

## Solution

The issue is solved by moving the functional component to the `app` directory or by using a page component in the `app` directory.