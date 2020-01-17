# GraphQL ultimate sandbox demo

## Tech Stack

* [Apollo](https://www.apollographql.com/docs/apollo-server/) – GraphQL Server
* [Dataloader](https://github.com/graphql/dataloader) – GraphQL Fetching Helper
* [Digital Ocean](https://www.digitalocean.com/) – Hosted Database
* [Knex](http://knexjs.org/) – SQL Query Builder
* [Pg-Node](https://node-postgres.com/) – Postgres NodeJS Client (used by Knex)
* [Micro](https://github.com/zeit/micro) – API Framework (used by NextJS)
* [NextJS](https://nextjs.org/) – React Framework
* [NodeJS](https://nodejs.org/) – Backend Platform
* [PostgreSQL](https://node-postgres.com/) – Database
* [React](https://reactjs.org) – Frontend View/Component Library
* [URQL](https://formidable.com/open-source/urql/) – GraphQL Client/Cache
* [URQL Devtools](https://github.com/FormidableLabs/urql-devtools) – URQL Devtools
* [Zeit](https://zeit.co/) – Hosting / Serverless Deploy

#### Possibly

* [Apollo Error Converter](https://www.npmjs.com/package/apollo-error-converter)

## Features

### Visitor

* Can view Posts
* Can view Blog
* Can login via GitHub

### Admin

* Can logout
* Can create Post
* Can edit (own) Posts
* Can view Accounts
* Can edit (own) Account

## Development

### Phase I (sandbox)

* [ ] 1. Backend: draft a NextJS app with API routes
* [ ] 2. Backend: make Apollo server work inside NextJS app
* [ ] 3. Backend: mock Blog/Post/User data (hardcode)
* [ ] 4. Frontend: implement Post page with manual fetching
* [ ] 5. Frontend: implement Post index page with manual fetching

### Phase II (working prototype)

* [ ] 6. Backend: error handling
* [ ] 7. Frontend: use URQL to fetch data
* [ ] 8. Frontend: error handling
* [ ] 9. Stack: deploy to Zeit
* [ ] 10. Stack: basic PROD/DEV deployments

### Phase III (MVP-1)

* [ ] 11. Stack: elaborate config / env aspect
* [ ] 12. Stack: integrate GitHub with Zeit
* [ ] 13. Stack: access DGO Postgres instance
* [ ] 14. Backend: serve data from Postgres (locally)
* [ ] 15. Stack: serve data from Postgres (cloud)

### Phase IV (MVP-2)

* [ ] 16. Backend: support authentication
* [ ] 17. Frontend: support authentication
* [ ] 18. Stack: implement authentication via Github (no security)
* [ ] 19. Stack: implement post-related Admin features
* [ ] 20. Stack: implement account-related Admin features

### Phase V (full MVP)

* [ ] 21. Backend: use Dataloader (+ Apollo contexts)
* [ ] 22. Stack: implement Post reordering
* [ ] 23. Stack: implement Post pagination
* [ ] 24. Stack: implement Post search/filtering
* [ ] 25: Stack: better auth security (say JWT or alternatives)

## Participants

Post your inquires [here](../../issues) 🕶️

--

Please ★ this repo if you're interested.
