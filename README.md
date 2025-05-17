# Simple Proxy

A lightweight reverse proxy designed to bypass CORS, powering [movie-web](https://movie-web.app). Full documentation at [docs.movie-web.app/proxy/introduction](https://docs.movie-web.app/proxy/introduction).

## Features

- **Multi-Platform Deployment**: Easily deployable across various platforms using Nitro.
- **Header Rewrites**: Read and write protected headers for flexible request handling.
- **CORS Bypass**: Enables seamless browser requests by bypassing CORS restrictions.
- **Turnstile Security**: Protect your proxy from bots with Cloudflare Turnstile integration.

> **Warning**: Turnstile integration is fully functional only on Cloudflare Workers.

## Supported Platforms

- Cloudflare Workers
- AWS Lambda
- Node.js
- Netlify (Edge Functions)
