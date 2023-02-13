# Процесс остановки  

1. **filebeat** 
на включном потоке перезапуска не желателен 

2. **logstash**
sudo systemctl stop logstach.service

3. **elasticsearch**
sudo systemctl stop elasticsearch.service

4. **kibana**
sudo systemctl stop kibana.service