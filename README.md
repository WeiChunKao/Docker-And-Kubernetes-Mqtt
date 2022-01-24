# mqtt
## Docker
docker build -t mqtt:latest .  
docker run --name mqtt -p 1883:1883 -p 9001:9001 mqtt:latest  
## K8s
提供mqtt.yaml，host需要安裝nfs server，PV、PVC需要更換路徑 
