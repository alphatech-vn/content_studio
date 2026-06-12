# Security Policy

If you believe you found a security or privacy issue related to Content Studio, please report it privately.

## Contact

- Email: `alphatech.digitolead@gmail.com`

If needed, include "Security" in the subject line.

## Please do not disclose publicly first

Do not open a public GitHub issue for:

- local file exposure,
- secret leakage,
- license bypass details,
- unsafe update behavior,
- provider key handling issues,
- any issue that could expose user data.

## What to include

Please include:

- a short summary,
- impact,
- reproduction steps,
- affected version if known,
- screenshots or logs with secrets redacted.

## Scope notes

Content Studio is a local-first desktop app. Security review should consider:

- local vault/file handling,
- API key storage,
- update/license traffic,
- outbound provider/API calls,
- source fetching from web/YouTube/GitHub,
- generated output handling.

## Disclosure handling

We prefer coordinated disclosure:

1. private report,
2. reproduction and assessment,
3. fix or mitigation,
4. user communication if required.

There is currently no public bug bounty program.
