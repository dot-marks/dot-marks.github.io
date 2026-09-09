# dotmarks.co.uk

The public site for the DotMarks app: overview, privacy policy, support and licences. Static HTML, no build step, served by GitHub Pages at the custom domain in `CNAME`.

Edit the HTML files directly and push to `main`. Pages redeploys on push.

## DNS (Fasthosts)

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| AAAA | @ | 2606:50c0:8000::153 |
| AAAA | @ | 2606:50c0:8001::153 |
| AAAA | @ | 2606:50c0:8002::153 |
| AAAA | @ | 2606:50c0:8003::153 |
| CNAME | www | dot-marks.github.io |

## Custom domain

Prerequisite: the records above resolve.

1. In the repository settings, open Pages and confirm `dotmarks.co.uk` as the custom domain.
2. Wait for the certificate, then tick Enforce HTTPS.

GitHub's procedure: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site
