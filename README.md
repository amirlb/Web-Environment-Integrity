# Web Environment Integrity API

This repository details the proposal to add a new API for determining the integrity
of web environments:

```js
const attestation = await navigator.getEnvironmentIntegrity("...");
```

The [explainer](./explainer.md) goes gives a high level overview of the proposal.

The [spec](https://rupertbenwiser.github.io/Web-Environment-Integrity/) currently describes how this is being prototyped in Chromium.

## Attestation of the complete web environment

As this API carries negative implications for user security and for the reputation of the web as a whole and of web browers,
a corresponding attestation mechanism for the web server will be specified and implemented in the near future.
