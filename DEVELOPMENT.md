## Development

Full details: https://github.com/eddiesigner/liebling/wiki/Theme-development-with-Docker

**NOTE: Run all dev commands in the src folder**

When setting up from scratch, you need to download database and start at an old Ghost version (v2) then upgrade the database, then go through each version in order changing it in the docker-compose file

## Edit Theme

If you get the `digital envelope routines::unsupported` error when running `npm run docker-watch`, switch to Node 16 or run with this openssl option:
```
NODE_OPTIONS=--openssl-legacy-provider npm run docker-watch
```
http://localhost:3000


## Production Build

```
NODE_OPTIONS=--openssl-legacy-provider npm run production
```
