# Notes
Try with .sslip.io suffix (e.g., http://123.45.67.89.sslip.io/)

For deployment, check diffs: https://github.com/compdemocracy/polis/compare/dev...Demos-thinktank:demos-dev

Add ENCRYPTION_PASSWORD_00001=[...] in VPS `server/docker-dev.env`
(optionally add) DOMAIN_WHITELIST_ITEM_01=[WHITELISTED_IP]

# Build commands
Build: `docker-compose build client-admin client-participation client-report`
Build participation: `docker-compose build client-participation`
Build admin: `docker-compose build client-admin`

Run: `docker-compose up --build --detach`

Build with no cache from previous builds: `docker-compose build --parallel --no-cache`

# Useful files
- `constants.js` (update character limit)

## ©️  License

[AGPLv3 with additional permission under section 7](/LICENSE)
