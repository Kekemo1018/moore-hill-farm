# Client Environment Setup

Moore Hill Farm is a separate client project from BABE/Blondies.

## What belongs in GitHub

- Public website files
- Safe placeholder values in `.env.example`
- Setup notes like this file

## What does not belong in GitHub

- `.env.local`
- Netlify tokens
- Form notification credentials
- Private client contact exports
- API keys, passwords, session tokens, or service-role keys

## Where real values belong

- Production values: the hosting platform's environment settings
- Local test values: `.env.local` on the developer machine only
- Company record: KM Logic's password manager under `Clients / Moore Hill Farm`

Do not reuse BABE, Blondies, or any other client credentials in this project.
