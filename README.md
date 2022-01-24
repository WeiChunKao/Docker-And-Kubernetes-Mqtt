# mqtt
# Docker
docker build -t mqtt:latest .  
docker run --name mqtt -p 1883:1883 -p 9001:9001 mqtt:latest  
