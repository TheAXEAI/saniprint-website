# SaniPrint DNS deployment

GitHub Pages is configured from the `main` branch, root directory, with the custom domain `saniprint.com`.

## WordPress.com DNS records

Remove the current WordPress.com website A records and add:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | TheAXEAI.github.io |

Optional IPv6 records:

- 2606:50c0:8000::153
- 2606:50c0:8001::153
- 2606:50c0:8002::153
- 2606:50c0:8003::153

Do not change mail-related MX or TXT records. After DNS propagation, enable **Enforce HTTPS** in Repository Settings → Pages.
