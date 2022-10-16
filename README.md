# **React Project Basic Settings**

Based `Webpack` and `Lerna` configured with `Typescript`

<br />

# Install

```console
yarn install
```

<br />

# Run

_If you run in VSCODE, Add prefix `yarn`_

**myapp**

```console
lerna run dev --scope=myapp
```

<br />

# Packages Tree

```text
├── README.md
├── babel.config.js
├── lerna.json
├── package.json
├── packages
│   └── myapp
│       ├── package.json
│       ├── public
│       │   └── index.html
│       ├── src
│       │   └── index.tsx
│       ├── tsconfig.json
│       └── webpack.config.js
├── tsconfig.json
├── webpack.config.js
└── yarn.lock
```