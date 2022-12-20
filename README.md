# maven_demo
grafana

docker run -d -p 3000:3000 --name grafana grafana/grafana-enterprise:8.2.0 

admin / admin

-- 아래는 아직
docker run -d \
  -p 3000:3000 \
  --name=grafana \
  -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
  grafana/grafana-enterprise