# Python Example

This example demonstrates how to call the `zeturf-scraper` actor using the Apify API Client.

**Note:** This example uses the `apify-client` package to call actors from external code.
If you want to create Actors, use the `apify` SDK package instead.

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set your Apify API token:
```bash
export APIFY_TOKEN=your_apify_token_here
```

4. Copy the template file and run it:
```bash
cp main.py.template main.py
python main.py
```

## Customization

Edit `main.py.template` (or copy it to `main.py` and edit) to customize the input parameters based on your actor's input schema.

## Documentation

For complete documentation on using the Apify API client for Python, see:
- [Apify API Client for Python Documentation](https://docs.apify.com/api/client/python/docs)
- [Apify Platform Documentation](https://docs.apify.com/)

