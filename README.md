docker-compose exec app bundle exec rake db:setup db:migrate
docker-compose up -d
docker-compose ps

# Go to a docker
sudo docker exec –it postgres /bin/bash