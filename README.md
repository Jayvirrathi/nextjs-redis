## Redis FullText Search with redis-om (ORM)

Build a fulltext instant-search feature with Redis & Next.js. 

### Usage

```
npm install
```

This demo requires that you have a Redis database running in the cloud or locally. Create a file named `.env.local` and export `REDIS_URL` with your connection details. Example: 

### docker 

```
docker run -p 6380:6379 redislabs/redismod:preview
```

```
REDIS_URL=redis://localhost:6380
```

### cloud url 

```
REDIS_URL=redis://default:PASSWORD@HOST:PORT
```


### Start Project [url](http://localhost:8080/)

```
npm run dev
```

### create Index for search 
```
http://localhost:8080/api/createIndex
```