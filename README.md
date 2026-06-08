# entra-access-evidence-ledger

Board-readable Kinetic Gain proof repo for **Microsoft Entra ID** signal coverage.

## Signal lane

- Vendor / platform: Microsoft Entra ID
- Domain: IAM / Security
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

Access evidence, conditional access posture, identity drift, and review readiness.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for Microsoft Entra ID without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.
