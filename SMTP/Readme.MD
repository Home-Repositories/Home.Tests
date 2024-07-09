docker compose up -d
docker exec -ti mailserver setup email add pawel@productivitytools.top
docker exec -ti mailserver setup config dkim
