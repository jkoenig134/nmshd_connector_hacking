# Connector TUI

> A terminal user interface for Demos.
>
> Showcase how to integrate Enmeshed and use the SDK.
>
> This TUI only works with Enmeshed v2 (Connector version 3.0.0+)

## Installation

Create a `.env` file in the folder you want to execute the TUI from and fill in the values:

```txt
BASE_URL=
API_KEY=
CONNECTOR_DISPLAY_NAME=
```

If you want to execute this TUI as a package you can install it using `npm i -g @nmshd/connector-tui@beta` and run `connector_tui` or simply run `npx @nmshd/connector-tui@beta`.

## Run Local / Dev Time

1. (only for the first time) `npm install` and copy `.env.example` to `.env` and fill in the values.
2. `npm start`
