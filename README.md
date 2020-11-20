# DelsihWish 2.0

![DelishWish Logo]()
This is a second version with my intial plans of Auth0 and GraphCMS.

### Overview

recipe to shopping list app

Next.js
Typescript
React
GraphQL
Apollo
GraphCMS https://graphcms.com/
GraphQL Code Generator https://graphql-code-generator.com/
Pluralize (for ingredients)
AuthO https://auth0.com/blog/ultimate-guide-nextjs-authentication-auth0/

### How to run this Project

Clone main branch
Create a .env file and add the following variables

```
BRANCH=master
GRAPHCMSURL=your-graph-cms-url
GRAPHCMSPROJECTID=your-graphcms-id
domain=your-domain.auth0.com
clientId=your-auth0-clientid
clientSecret=your-auth0-clientSecret
scope='openid profile'
redirectUri=https://localhost:3000/api/callback
postLogoutRedirectUri=https://localhost:3000/
cookieSecret='one-two-three-secret-four-secret-dont-share-it-ever'
BACKEND_URL=https://localhost:3000/api/graphql
GRAPHCMS_TOKEN=your-graphcms-token
APIURL=https://www.filestackapi.com/api/store/S3
APIKEY=your-graphcms-api-key
PROJECTID=your-graphcms-projectid
CDNBASE=https://cdn.filestackcontent.com/
```

Run npm install to add dependencies
View on local server
