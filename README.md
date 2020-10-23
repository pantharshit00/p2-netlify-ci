# Netlify + Prisma

Prisma and Netlify integration.

## How to run this locally

### Netlify authentication

A netlify token needs to be set with the environment variable `NETLIFY_AUTH_TOKEN`.

Alternatively, you can login using `netlify login`.

### Environment variables

The environment variable `NETLIFY_BETA_PG_URL` should point to a postgres database.

Please check our internal 1Password E2E vault for a ready-to-use environment variable or  
set up your own database and set the environment variable accordingly.

### Run Locally

```shell script
netlify dev
```

### Deploy

Use nelify's git integration. In build command, put the value `yarn`

