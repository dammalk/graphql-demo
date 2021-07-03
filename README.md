# graphql-demo
Coded along to GraphQL-Node tutorial from Robin MacPherson

Source: https://www.howtographql.com/graphql-js/0-introduction/

## Frameworks and libraries

- [Node.js](https://nodejs.org/en/)
- [GraphQL](https://graphql.org/learn/)
- [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
- [Prisma](https://www.prisma.io/docs/)
- [SQLite](https://www.sqlite.org/docs.html)
- [JsonWebToken](https://github.com/auth0/node-jsonwebtoken)
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs)

## Commands

- `node src/index.js` - runs the project
- `npx prisma init` - initializes Prisma
- `npx prisma migrate dev --name "name-of-the-migration"` - creates migrations
- `npx prisma generate` - generates Prisma CLient _~need to re-generate it after every migration!_
- `npx prisma studio` - opens Prisma GUI database editor

### Install commands
```
npm install apollo-server
npm install graphql
npm install prisma --save-dev
npm install @prisma/client
npm install jsonwebtoken
npm install bcryptjs
```
