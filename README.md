
# Country Capital API

Provides the Country name if provided with Capital

## API Reference

#### Get country name

```http
  GET https://example.com/country-capital/<query-params>
```

## Prerequisites

This project assumes that you have already installed python3 to run locally.
## Local development setup

Create virtual environment

```bash
  python -m venv venv
```

Activate virtual environment

```bash
  ./venv/bin/activate
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  uvicorn app:asgi_app
```
