# Notes
export DOMAIN_WHITELIST_ITEM_01=[WHITELISTED_IP]
Try with .sslip.io suffix (e.g., http://123.45.67.89.sslip.io/)

For deployment, check diffs: https://github.com/compdemocracy/polis/compare/dev...Demos-thinktank:demos-dev


# Build commands
Build: `docker-compose build client-admin client-participation client-report`
Build participation: `docker-compose build client-participation`
Build admin: `docker-compose build client-admin`

Run: `docker-compose up --build --detach`

Build with no cache from previous builds: `docker-compose build --parallel --no-cache`

# Useful files
- `constants.js` (update character limit)

# TODO
- Set/encourage minimum of 7 votes
- Notify video server to continue video

## ©️  License

[AGPLv3 with additional permission under section 7](/LICENSE)
