## Filebeat, Logstash, ELK 예제 

Filebeat, Logstash, ELK 예제입니다. Filebeat로 수집한 로그 (logs/new-log.log) 를 logstash 에 전달하고 logstash는 이를 가공하여 Elastic Search에 전달합니다. ibana를 통해 로그를 시각화하여 볼 수 있습니다. 

## 실행 방법 

```
docker compose up -d
```

이후 http://localhost:5601/app/kibana 로 접속하여 index pattern을 생성하고 discovery 탭으로 이동해 파싱된 로그를 확인합니다. 
