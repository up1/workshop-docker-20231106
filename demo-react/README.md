# React + TypeScript + Vite

## Development process

### Normal process
```
$npm install
$npm run dev
```

Open url = http://localhost:5173/ in web browser

### Working with docker compose
```
$docker compose -f docker-compose-dev.yml up -d
$docker compose -f docker-compose-dev.yml ps
```

Open url = http://localhost:8000/ in web browser


## Production process
```
$npm install
$npm run build
```

Copy all files and folders in /dist to production server

### Working with docker
* Create Dockerfile
* Create docker-compose.yml

Run
```
$docker compose build
$docker compose up -d
```

Open url = http://localhost:8888/ in web browser