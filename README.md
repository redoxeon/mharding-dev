# mharding dot dev

[![Netlify Status](https://api.netlify.com/api/v1/badges/28a3a823-d8d7-4476-a32f-93c6223f3783/deploy-status)](https://app.netlify.com/sites/mharding-dev-3925f/deploys)

## Stackbit Fresh Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.73.

## Running Your Site Locally

1.  [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1.  get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1.  run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1.  run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5d93925f3003100013bb5ab5

1.  Build the site and start the Hugo server with drafts enabled

        hugo server -D

1.  Browse to [http://localhost:1313/](http://localhost:1313/)
