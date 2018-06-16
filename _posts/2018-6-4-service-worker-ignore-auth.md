---
layout: post
title: 'June 4, 2018'
---

- How to ignore authentication routes in Preact service worker

## How to ignore authentication routes in Preact service worker

### Problem

Preact CLI generates sw.js on build using [sw-precache](https://github.com/GoogleChromeLabs/sw-precache). The default configuration intercepts routes like `/auth/github` wich not defined in the frontend implementation and returns the fallback route. It therefore breaks the authentication flow.

### Solution

- Install **preact-cli-sw-precache**

```bash
npm i -D preact-cli-sw-precache
```

- Create a preact configuration file in your project root folder (`preact.config.js`) and extend the default configuration to negate the specific route:

<script src="https://gist.github.com/felipewer/da39cb2f11408a690abf4cd9fbc381c8.js"></script>

Options specified in **precacheConfig** are merged with the existing configuration.

### Resources

[Preact-cli and service worker (Post)](https://medium.com/@prateekbh/preact-cli-and-service-worker-2e0f034157e7)

[preact-cli-sw-precache (repo)](https://github.com/prateekbh/preact-cli-sw-precache)

[sw-precache (repo)](https://github.com/GoogleChromeLabs/sw-precache)

[Stack Overflow answer](https://stackoverflow.com/a/48649266)