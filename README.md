# Heroku Python Cookie Cutter

A boilerplate template for deploying Python applications on Heroku, with a built-in logging utility.

## Tech Stack

- Python
- aiohttp
- Heroku

## Features

- Reusable logging module (`lib/logtaker.py`) with file + stdout output
- Heroku deployment configuration (`runtime.txt`, `Procfile`)
- Environment file placeholder

## Setup

```bash
pip install -r requirements.txt
```

## Deploy to Heroku

```bash
heroku create
git push heroku master
```

## Project Structure

```
├── .env               # Environment variables
├── requirements.txt
├── runtime.txt        # Python runtime for Heroku
└── lib/
    └── logtaker.py    # Logging utility
```
