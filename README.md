# kafka-with-elk

docker compose 로 만든 kafka + elasticsearch + logstash + kibana + kafdrop + zookeeper 용 도커 컴포즈 파일입니다

사용한 Topic은 'kafka-elk' 입니다.

또한, 사용을 하기 위해서는 아래 내용을 수정해야 합니다

1. /etc/hosts 수정 필요

   127.0.0.1 kafka 추가
