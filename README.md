![node.js is shiny](http://roshangrewal.com/junk/node.gif)

## Blogster Node App with React, MongoDB, Redis, Google Auth and AWS S3

[![Build Status](https://travis-ci.org/roshangrewal/blogster-mern.svg?branch=master)](https://travis-ci.org/roshangrewal/blogster-mern)

https://github.com/coding-to-music/blogster-mern

By Roshan Grewal https://github.com/roshangrewal

https://github.com/roshangrewal/blogster-mern

1. Setup

- Clone Repo
- Run `npm install`
- Create an `.env` file in project's root directory and add the following properties:

| Prop                  | Value  |                           Description |
| --------------------- | :----: | ------------------------------------: |
| AWS_ACCESS_KEY_ID     | String |                   Your AWS access key |
| AWS_ACCESS_KEY_SECRET | String |             Your AWS access key scret |
| AWS_BUCKET            | String |               Your AWS S3 Bucket name |
| AWS_REGION            | String |             Your AWS S3 Bucket region |
| GOOGLE_CLIENT_ID      | String |             Your Google Credential ID |
| GOOGLE_CLIENT_SECRET  | String |         Your Google Credential Secret |
| MONGO_URI             | String |                 MongoDB connectio URL |
| APP_COOKIE_KEY        | String | Random string to be used with cookies |
| REDIS_URL             | String |                    Redis instance URL |

2. Run
   Execute `npm run dev` from CLI. This starts the backend on port `5000` and the React frontend on port `3000`, with a proxy from `3000` to `5000`

3. Run tests
   Run `npm run test` from CLI
