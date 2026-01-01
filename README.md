# STONKS - Cannabis Stock Screener

**Exposing the mispricing between US MSOs and Canadian LPs**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## The Problem

Canadian Licensed Producers (Tilray, Canopy, Aurora, Cronos, SNDL) often rally on US federal reform news—**but they receive zero benefit**.

| Reform Catalyst | US MSO Impact | Canadian LP Impact |
|-----------------|---------------|-------------------|
| 280E Elimination | **$2B+ annual tax savings** | $0 |
| SAFE Banking | **Traditional banking access** | Already have it |
| Schedule III | **40-70% profitability boost** | No change |

This screener helps investors identify which companies *actually* benefit from reform versus which are riding momentum disconnected from fundamentals.

## Live Site

**[stonks.dankreports.com](https://stonks.dankreports.com)**

## Features

- **25 Cannabis Stocks** tracked across US MSOs, Canadian LPs, and International operators
- **280E Tax Burden Estimates** for each US MSO ($604M combined annual burden)
- **BMDE Framework Scoring** - State-level market quality analysis (r=0.968 validated)
- **Reform Upside Multiples** - Estimated P/E expansion from 280E elimination
- **Canadian LP Warnings** - Clear callouts when companies have no reform exposure
- **Filtering & Sorting** - By company type, 280E exposure, market cap, CBDT score

## Coverage

### US MSOs (280E/SAFE Banking Impacted)
TCNNF, CURLF, GTBIF, CRLBF, VRNOF, TRSSF, CCHWF, JUSHF, GLASF, SHWZ, PLNHF, MRMD, GDNSF, NVACF

### Canadian LPs (No Reform Impact)
TLRY, CGC, ACB, CRON, SNDL, VFF, OGI, HITI, LOVFF, CBWTF

### International
INCR

## BMDE Framework

The Black Market Death Equation is a validated predictive framework for legal cannabis market share.

**Formula:** `ΔU = 4(−g) + D + 1.2S + F + 0.6E − 0.8F_frag`

**Validation:**
- Correlation: r = 0.968 across 6 US states
- Mean Absolute Error: 5%
- Directional Accuracy: 87.5% (21/24)

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- React 18 (via CDN)
- Tailwind CSS (via CDN)
- No build step required

## Local Development

```bash
# Clone the repository
git clone https://github.com/Dan-K-Reports/stonks.git
cd stonks

# Serve locally (Python)
python -m http.server 8000

# Or with Node
npx serve
```

Open `http://localhost:8000` in your browser.

## Deployment

This is a static site. Deploy to:

- **GitHub Pages** - Push to `main` branch, enable Pages in Settings
- **Netlify** - Connect repo, auto-deploys on push
- **Vercel** - Connect repo, auto-deploys on push
- **Cloudflare Pages** - Connect repo, auto-deploys on push

## Data Sources

- Market data compiled from public sources (Yahoo Finance, company filings)
- 280E burden estimates based on reported EBITDA and industry tax analysis
- State footprints from company investor presentations and 10-K filings
- CBDT scores from validated framework developed by Daniel Kief

## Disclaimer

This tool is for informational purposes only. Not financial advice. Data may be delayed or inaccurate. Always conduct your own due diligence before making investment decisions.

## License

Content and data licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

CBDT Framework developed by Daniel Kief.

## Author

**Daniel Kief**
- Website: [dankreports.com](https://www.dankreports.com)
- Email: [danielkreports@gmail.com](mailto:danielkreports@gmail.com)
