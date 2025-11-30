<img src="AppIcon-Dark.svg" alt="OAuth42" width="80" align="left" style="margin-right: 16px;">

# OAuth42

**Enterprise Authentication for Modern Applications**

<br clear="left">

OAuth42 is a SaaS authentication provider implementing OAuth 2.0 and OpenID Connect with multi-factor authentication. Built for everyone from solo developers shipping their first app to enterprises with complex security requirements.

**[Get started at oauth42.com](https://oauth42.com)**

## SDKs

| Platform | Package | Installation |
|----------|---------|--------------|
| **Next.js** | [@oauth42/next](https://www.npmjs.com/package/@oauth42/next) | `npm install @oauth42/next` |
| **Rust** | [oauth42](https://crates.io/crates/oauth42) | `cargo add oauth42` |
| **Swift** | [oauth42-swift](https://github.com/oauth42/oauth42-swift) | Swift Package Manager |

## Tutorials

Get started with OAuth42 integration:

- [Getting Started with Hosted Auth (Next.js)](https://oauth42.com/docs/tutorials/hosted-auth-nextjs) - Integrate hosted authentication pages
- [Python Service Authentication](https://oauth42.com/docs/tutorials/python-service-auth) - Server-to-server authentication
- [OIDC Discovery Quickstart](https://oauth42.com/docs/quickstart-oidc) - Auto-configure with OpenID Connect

## Features

- **OAuth 2.0 & OIDC** - Full OAuth 2.0 Authorization Code Flow with PKCE and OpenID Connect
- **Multi-Factor Authentication** - TOTP-based MFA with Microsoft Authenticator-style codes
- **Multi-Tenant Architecture** - Company and organization management with role-based access
- **FIPS 140-2 Compliant** - Validated cryptography for federal and enterprise requirements
- **SOC2 Type II Ready** - Built with security, availability, and compliance in mind
- **Real-time Updates** - WebSocket support for live authentication events

## Documentation

- [API Reference](https://oauth42.com/docs/api)
- [OIDC Discovery](https://oauth42.com/docs/oidc-discovery)
- [Security & Compliance](https://oauth42.com/docs/compliance)
- [Deployment Guide](https://oauth42.com/docs/deployment)

## Quick Example (Next.js)

```typescript
import { createAuth } from '@oauth42/next';

export const { handlers, auth } = createAuth({
  scopes: ['openid', 'profile', 'email'],
});

export const { GET, POST } = handlers;
```

## Links

- [Website](https://oauth42.com)
- [Customer Portal](https://app.oauth42.com)
- [Status Page](https://status.oauth42.com)
- [Support](mailto:support@oauth42.com)

---

Copyright © 2024 OAuth42, Inc. All rights reserved.
