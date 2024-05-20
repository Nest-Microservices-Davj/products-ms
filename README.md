# Product Microservice

## Dev
1. Clone repository
2. Install dependencies
3. Create `.env` file on base of `.env.template`
4. Run Prisma migration `npx prisma migrate dev`
5. Start NATS server 
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Run `npm run start:dev` 