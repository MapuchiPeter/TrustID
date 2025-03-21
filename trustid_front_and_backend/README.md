# TrustID: Blockchain-Powered Digital Identity Verification

TrustID is a blockchain-powered digital identity verification system that ensures secure, tamper-proof, and verifiable credentials. TrustID allows users to manage and share their credentials (e.g., National ID, Passports, Degrees) with organizations in a privacy-preserving, decentralized way.

<p align="center">
  <img src="https://github.com/Nexa-Bites/trustid_front_and_backend/blob/main/WhatsApp%20Image%202025-03-20%20at%2013.23.22_3df22ccf.png?raw=true" alt="TrustID Logo" width="250">
</p>

---

## 📌 Our Mission
To provide a trustworthy, efficient, and privacy-centric digital identity system for seamless verification across industries like **finance, healthcare, education and more**.

---
## 🏠 TrustID | Signup Now
[🌐 Visit TrustID App](https://trust-id-snowy.vercel.app/)


## 🔹 Key Features
- ✅ **Decentralized Identifiers (DIDs)** for secure user authentication.
- ✅ **Verifiable Credentials** stored on blockchain for authenticity.
- ✅ **Automated Data Extraction** using OCR/AI for easy document verification.
- ✅ **Revocation Registry** to track and prevent fraudulent credentials.
- ✅ **Seamless Integration** for organizations to verify credentials in real-time.

---

## 📊 Project Presentation And Documentaion Summary

[➡️ Presenation: Click here to view the Google Slides](https://docs.google.com/presentation/d/1P1hOViR7TNffz5H2b4t8dL0hz_HxIsuIRW3yM1SCKPs/edit#slide=id.g3446bf115aa_0_15)

[📑 Project Summary: View Google Doc](https://docs.google.com/document/d/1fH9gBXEnQuEC7aTgMOzYQs4nQfhRIcNT883S0Sb38Ns/edit?usp=sharing)




# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```
