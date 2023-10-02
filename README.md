# Stack one - Headless SSG

## Frontend
- Nuxt SSG
- Nuxt image
- Tailwind css

## Cms
- Statamic
  + Statamic pro is required for headless setup

## Deployment cms
- Shared hosting or docker container vps
  + Shared hosting is maintanance free 
  + Speed is not important

## Deployment frontend
- Cloudflare pages SSG (nuxt generate)
  + Max 25mb for each asset (should be fine for all images and pages)
  + Larger assets such as video's can be loaded from other storage solutions such as S3 (cloudflare r2 bucket with S3 api) (https://statamic.dev/assets#containers)
  + Alternative could be Netlify, Vercel or Deno Deploy
- Github
  + Linked repo to Cloudflare
 
## Costs
- €5 monthly for cms hosting
- €250 for Statamic cms


# Stack two - Headless SSR

## Frontend
- Nuxt SSR
- Nuxt image
- Tailwind css

## Cms
- Strapi
  + has GET and POST api

## Deployment cms
- Docker container on vps

## Deployment frontend
- Docker container on vps
- Cloudflare CDN
  



