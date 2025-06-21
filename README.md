# HTML Crawler Downloader

A Python-based website crawler using Selenium that extracts and saves each internal page as an `.html` file — complete with all CSS, JS, and image assets.

## Features

- Uses headless Chrome via Selenium
- Crawls all internal links on a site
- Downloads and rewrites all linked assets
- Saves each page locally in `.html` format
- Skips duplicate pages and inline assets

## Getting Started

### Prerequisites

- Python 3.8 or later
- Google Chrome
- ChromeDriver (matching your browser version and available in system PATH)

### Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/omarhossam214/html-crawler-downloader.git
cd html-crawler-downloader
pip install -r requirements.txt
