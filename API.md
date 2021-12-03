# API
렘 API의 엔드포인트 및 사용 방법을 안내합니다.

# BASE_URL
본 API 의 BASE URL 은 2개로 나뉩니다.
HTTP 프로토콜을 사용하는 API BASE URL 은 아래와 같습니다.
```css
http://api.rem9999.xyz/
```
HTTPS 프로토콜을 사용하는 API BASE URL 은 아래와 같습니다.
```css
https://218.147.251.17:2/
```
> ```__2개로 나누는 이유__```
> HTTPS 프로토콜에서 HTTP 프로토콜에 requset 요청을 CROS 정책으로 인해 전송하지 못합니다.
> HTTPS 프로토콜은 jquery / 웹 개발 하시는분들이 사용하시면 됩니다.
> 디스코드 봇 및 node-fetch, requset 와 같은 모듈 사용하시는 분들은 HTTP 프로토콜 사용하셔도 상관 없습니다,


# 버전
V2 버전은 API_KEY 를 지원할 예정입니다.
현재는 BASE_URL 에 버전을 표기하지 않습니다.

| 버전     | 상태   |
|---------|-------|
|   2    |개발중|
|   1    |지원중|
|   0    |사용 불가|