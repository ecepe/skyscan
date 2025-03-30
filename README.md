# SkyScan

**Scan your cloud. Catch known threats. Instantly.**

SkyScan is a one-click cloud threat intelligence tool. Enter your IP ranges or cloud assets, and SkyScan will instantly match them against top threat intelligence feeds like CISA KEV, AbuseIPDB, and GreyNoise.

## Features

- Real-time matching against public threat feeds
- Input your IPs, CIDRs or cloud ranges
- CSV & JSON export of matches
- No login or install required (web version)
- Open-source & extensible

## Use Cases

- Security engineers checking exposure
- Cloud admins validating IP risk
- Blue teams enhancing visibility
- MSSPs performing fast recon for clients

## Getting Started

Clone the repo, run locally with Docker, or use the hosted version (coming soon).

```bash
git clone https://github.com/ecepe/skyscan.git
cd skyscan
docker compose up
