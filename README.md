# Template Batch Generator

A tiny web tool to generate batch text outputs from a CSV + template.

## Why
People frequently ask for "template automation" and "batch generation" in communities.
This MVP lets users paste CSV data and generate personalized text in one click.

## Features
- CSV input (header + rows)
- Placeholder replacement with `{{field}}`
- Filename pattern support (`{{name}}.txt`)
- Download all generated outputs as one text bundle

## Run locally
Just open `index.html` in browser.

## Deploy
Designed for static hosting on Vercel.
