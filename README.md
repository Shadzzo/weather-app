# Weather App in Nuxt3

![Image of the App](https://i.imgur.com/PtiOxRH.png)

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Known Issues

Searching a city for the second time does not update the rendered info. Requesting a third time and so on works.
