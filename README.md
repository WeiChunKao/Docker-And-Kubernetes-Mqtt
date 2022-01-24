# mqtt
docker build -t mqtt:latest .
docker run --name mqtt -p 1883:1883 mqtt:latest
