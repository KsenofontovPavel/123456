# Процесс запуска  

1. **filebeat** 
*на включном потоке перезапуск не желателен!*

2. **logstash**
*sudo systemctl stop logstach.service*

3. **elasticsearch**
*sudo systemctl stop elasticsearch.service*

4. **kibana**
*sudo systemctl stop kibana.service*

# Процесс остановки

1. **kibana**
*sudo systemctl stop kibana.service*

2. **elasticsearch**
*sudo systemctl stop elasticsearch.service*

3. **logstash**
*sudo systemctl stop logstach.service*

4. **filebeat** 
*на включном потоке перезапуск не желателен!*