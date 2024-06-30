---
title: Configuration
description: Configuring your Next.js project
---

# Configuration

## next.config.js

Next.js can be customized using the `next.config.js` file in the root of your project.

### Example Configuration

```js
module.exports = {
  reactStrictMode: true,
  images: {
    domains: ['example.com'],
  },
};
