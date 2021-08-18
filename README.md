### run dev server

docker-compose -f docker-compose.yml -f docker-compose-dev.yml up -d --build

### build prd(nginx)

docker-compose -f docker-compose.yml -f docker-compose-prd.yml up -d --build
