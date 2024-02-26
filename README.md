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
