# Realtime chat example using Supabase

This is a full-stack Slack clone example using:

- Frontend:
  - Next.js.
  - [Supabase.js](https://supabase.com/docs/library/getting-started) for user management and realtime data syncing.
- Backend:
  - [app.supabase.com](https://app.supabase.com/): hosted Postgres database with restful API for usage with Supabase.js.

## Demo

- Live demo: https://slack-clone-pk5r.vercel.app

![Demo animation gif](./public/slack-clone-demo.gif)


## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example locally:

```bash
npx create-next-app --example with-supabase-auth-realtime-db realtime-chat-app
# or
yarn create next-app --example with-supabase-auth-realtime-db realtime-chat-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/vercel/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-supabase-auth-realtime-db
cd with-supabase-auth-realtime-db
```

### Using this repo

Simply clone this repo locally and proceed to the next section.

### Required configuration

Copy the `.env.local.example` file into a file named `.env.local` in the root directory of the example:

```bash
cp .env.local.example .env.local
```

Set your Supabase details from [step 3](#3-get-the-url-and-key) above:

```bash
NEXT_PUBLIC_SUPABASE_URL=<replace-with-your-API-url>
NEXT_PUBLIC_SUPABASE_KEY=<replace-with-your-anon-key>
```

### Change authentication settings if necessary

Follow [Step #5](#5-change-authentication-settings-if-necessary) above if you want to change the auth settings.

### Run the development server

Now install the dependencies and start the development server.

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Visit http://localhost:3000 and start chatting! Open a channel across two browser tabs to see everything getting updated in realtime 🥳



## Authors

- [Supabase](https://supabase.com)

Supabase is open source, we'd love for you to follow along and get involved at https://github.com/supabase/supabase
