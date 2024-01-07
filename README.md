# compiiile-actions-cloudflare-pages
A simple Github action to deploy a Compiiile site to CloudFlare page

[Compiiile is a very clever, simple and beautiful Markdown to Website tranformer, get it here](https://github.com/compiiile/compiiile)

But when you need to have multiple websites on a monorepo it can be difficult to simply use Netlify, Cloudflare Pages or Vercel to get multiples subdomains / site from 1 repo.

With this actions you can easily use the working directory and publish to cloudflare recipe to deploy several sites from a simple repository

## About Actions Secrets 
It can be a huge waste of time to understand from where Github Actions pull its `secrets` or `env` variables from your repository (for `ACCOUNT_ID` and `CLOUDFLARE_API_TOKEN` for example) so read this : https://stackoverflow.com/a/67998780/2474454