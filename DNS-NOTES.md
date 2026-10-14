# DNS notes for volitiondynamics.com

DNS host: Squarespace (nameservers nsb1-4.squarespacedns.com).
Captured: 2026-10-13, before pointing the domain at GitHub Pages.

## Original records (Squarespace site), to restore if needed

| Host | Type | Value |
|---|---|---|
| `@` | A | 198.49.23.144 |
| `@` | A | 198.49.23.145 |
| `@` | A | 198.185.159.144 |
| `@` | A | 198.185.159.145 |
| `www` | CNAME | ext-sq.squarespace.com |

## Records to leave alone (email / verification)

| Host | Type | Value |
|---|---|---|
| `@` | MX | 10 smtp.google.com |
| `@` | TXT | google-site-verification=WgPpg_V5Fc-RRQR6DBI_7MD7E9whwoDMoY_X04KKTug |
| `@` | TXT | v=spf1 include:_spf.google.com -all |

No AAAA or CAA records existed.

## GitHub Pages records (replace the A and CNAME rows above)

| Host | Type | Value |
|---|---|---|
| `@` | A | 185.199.108.153 |
| `@` | A | 185.199.109.153 |
| `@` | A | 185.199.110.153 |
| `@` | A | 185.199.111.153 |
| `www` | CNAME | etucker671.github.io |

IPv6 (AAAA) records skipped because the site is temporary.
Source: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
