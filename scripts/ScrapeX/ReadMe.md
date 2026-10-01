# How to Scrape Twitter without Authentication

Code examples for the blog post **["How to Scrape Twitter without Authentication: Gaffa Guide)"](https://gaffa.dev/blog/how-to-scrape-twitter-without-authentication-gaffa-guide))** using the [Gaffa Browser Request API](https://gaffa.dev).


## Requirements

- Python 3.8+
- A Gaffa API key — sign up at [gaffa.dev](https://gaffa.dev) and create your key in the **API Keys** section of the dashboard

## Setup

**1. Clone the repo**
```bash
git clone https://github.com/GaffaAI/GaffaPythonExamples.git
cd scraping-tables
```

**2. Install dependencies**
```bash
pip install requests beautifulsoup4 python-dotenv
```

**3. Add your API key**

Create a `.env` file in the root of the project:
```bash
GAFFA_API_KEY=your_key_here
```