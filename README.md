# TinyPKI CSR/PKCS12 Generator Library

A part of TinyPKI project, with the intention to facilitate higher adoption of mTLS.

## Features
* Client-side PKCS#10 Certificate Signing Request (CSR) generation using Web Crypto API key pairs (supported: RSA/ECDSA/Ed25519);
* Bundling PEM certificate chain and private key together into PKCS#12 container (`.P12` or `.PFX` file);

## Demo

See the **[library demo](https://icedevml.github.io/tinypki-csr/)** for further reference.

## Installation

This library is distributed in two formats.

### ESM library
Suitable for SPA frameworks (like React.js), available on NPM Registry as [@icedevml/tinypki-csr](https://www.npmjs.com/package/@icedevml/tinypki-csr).

```bash
npm install --save @icedevml/tinypki-csr
yarn add @icedevml/tinypki-csr
```

### Single-file JavaScript bundle
Suitable for usage on classic HTML5 web pages, without requiring any external dependencies.
The entire bundle is approximately 500 kB.

Download: **[tinypki-csr.js](https://github.com/icedevml/tinypki-csr/releases)**

## Usage

See [`demo/`](https://github.com/icedevml/tinypki-csr/tree/master/demo) directory for usage examples.

## Manual building

After cloning the repository, run the following commands:
```
yarn
yarn build
```
