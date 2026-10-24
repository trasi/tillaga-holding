# tillaga-holding

Holding page for https://tillaga.is while the project is paused.
Served by GitHub Pages from the `main` branch. The product repo is `trasi/tillaga`.

## DNS (Route 53 zone `Z08811203NQOJSR2H4ACG`)

Web records added for the hold:

| Name | Type | Value |
| --- | --- | --- |
| `tillaga.is` | A | `185.199.108.153` `185.199.109.153` `185.199.110.153` `185.199.111.153` |
| `tillaga.is` | AAAA | `2606:50c0:8000::153` `2606:50c0:8001::153` `2606:50c0:8002::153` `2606:50c0:8003::153` |
| `www.tillaga.is` | CNAME | `trasi.github.io` |

Mail stays on Google Workspace: the MX, SPF, DKIM and DMARC records, and the
SendGrid CNAMEs, are untouched. To resume the product, replace the three web
records above and remove the custom domain from this repo's Pages settings.
