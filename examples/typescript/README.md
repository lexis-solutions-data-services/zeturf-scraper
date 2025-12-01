# TypeScript Example

This example demonstrates how to call the `zeturf-scraper` actor using the Apify API Client.

**Note:** This example uses the `apify-client` package to call actors from external code.
If you want to create Actors, use the `apify` SDK package instead.

## Setup

1. Install dependencies:

```bash
npm install
```

2. Set your Apify API token:

```bash
export APIFY_TOKEN=your_apify_token_here
```

3. Copy the template file and run it:

```bash
cp index.ts.template index.ts
npm start
```

## Customization

Edit `index.ts.template` (or copy it to `index.ts` and edit) to customize the input parameters based on your actor's input schema.

## Documentation

For complete documentation on using the Apify API client for JavaScript/TypeScript, see:
- [Apify API Client for JavaScript Documentation](https://docs.apify.com/api/client/js/docs)
- [Apify Platform Documentation](https://docs.apify.com/)
