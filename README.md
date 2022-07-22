# prisma-reproducible-example

## Run

```bash
npm i
npm run prisma:generate
npm run prisma:migrate-deploy
npm start
```

## Setup Demo

1. Create a `.env` file and provide a `DATABASE_URL` environment variable
2. Create you demo prisma schema in `prisma/schema.prisma`
3. Apply your schema changes via `npm run prisma:migrate-dev`
4. Write your code resulting in the bug you want to showcase in `src/index.ts`
