
#!/usr/bin/env bash
set -e

echo "Cal.com Azure deployment helper"
echo "1) sudo apt update"
echo "2) sudo apt install docker.io docker-compose -y"
echo "3) git clone https://github.com/calcom/cal.com.git"
echo "4) cd cal.com"
echo "5) cp .env.example .env  # fill DATABASE_URL and auth keys"
echo "6) docker compose up -d"
echo "7) open browser and test application"
