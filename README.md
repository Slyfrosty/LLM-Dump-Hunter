# LLM Dump Hunter

LLM Dump Hunter is a Termux-ready Python tool that scans `.txt` and `.json` files for leaked credentials, secrets, and sensitive data.

### Features

- Detects:
  - API Keys (Stripe, Firebase, AWS, OpenAI, etc.)
  - Private Keys
  - JWTs
  - Email addresses
  - Crypto wallet seed phrases
  - .env config secrets
  - Base64 encoded blobs

### Usage

```bash
python llm_dump_hunter.py
