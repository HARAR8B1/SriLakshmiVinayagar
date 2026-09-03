# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:


## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and Oxlint's TypeScript related rules in your project.
# Sri Lakshmi Vinayagar Temple

A responsive React + Vite static website for Sri Lakshmi Vinayagar Temple, Thiruninravur, Chennai.

## Run locally

```bash
npm install
npm run dev
```

Build for deployment with `npm run build`; deploy the generated `dist` folder to any static host.

## Content administration

Select **Admin login** and use the static demo credentials `admin` / `H@ri9831`. Edits are saved to browser `localStorage`.

The demo intentionally leaves temple timings, poojas, history, festivals, and contact data marked for administration rather than inventing unverified information.

This frontend-only login is not secure for production. Use Firebase Auth, Supabase Auth, or a custom server with protected storage before deploying publicly.

## Stack

React, Vite, Tailwind CSS dependencies, Lucide React, Axios-ready dependency, React Hook Form, Zod, and `@hookform/resolvers`.
