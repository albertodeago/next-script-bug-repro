This is a repo to reproduct a (possible) bug of the Next/Script component.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open the console, two dom elements (script tags) are being printed. the two elements
are created with the same attributes except for the strategy.  
The resulting DOM element has different attributes (e.g. defer and crossorigin)
