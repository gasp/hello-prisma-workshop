# prisma workshop

## install
* `npm install` to install dependencies
* `npx prisma generate` to generate the Prisma client
* `npx prisma migrate dev` to create the database

## run
* `npm start` console logs 2 authors with their posts

# deploy
* `npx prisma generate` to generate prisma client (only if needed)
* `npm run build` to build the project
* `npx prisma migrate deploy` to deploy the database schema
* `npm run start:prod` to start the production server
