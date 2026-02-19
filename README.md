# SampleFlask

A lightweight **Flask** frontend for the Projects Portfolio API. Displays your projects and individual project detail pages.

## Features

- Homepage listing all projects fetched from the portfolio API
- Individual project detail pages
- Clean, minimal HTML/CSS

## Setup

### Prerequisites
- Python 3.12+
- Pipenv

### Install dependencies

```bash
pipenv install
```

### Run locally

```bash
pipenv run python app.py
```

The app will start at `http://localhost:5000`.

## Configuration

The API base URL is set in `app.py`. Update `PROJECTS_API_URL` and `PROJECT_API_URL` to point to your deployed portfolio API instance.

## Tech Stack

- Python / Flask
- Jinja2 templates
- Requests
