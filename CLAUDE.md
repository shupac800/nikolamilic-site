# nikolamilic-site

Static site for Nikola Milic — The Euroshredder.

## Deployment

Hosted on Lightsail at `/var/www/nikola.shupac.com`, served by nginx with SSL.

To deploy updates:

```
ssh lightsail "cd /var/www/nikola.shupac.com && sudo git pull"
```
