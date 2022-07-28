# Docker Compose Collection

> docker-compose collecion

## Getting Started

필요한 컨테이너가 있는 폴더에서 아래 명령어를 실행

```bash
docker-compose up -d
```

## Docker Command Usage

1. -f

현재 폴더의 default 설정 파일인 `docker-compose.yml` 대신 다른 설정 파일을 사용해야 할 경우 **-f** 옵션을 사용한다.

```bash
 docker-compose -f docker-compose-local.yml up
```

2. up

Docker Compose에 정의되어 있는 모든 서비스 컨테이너를 한 번에 생성 후 실행
`-d` 옵션을 추가해 백그라운드에서 컨네이너를 실행하는 경우가 많다.

3. down

Docker Compose에 정의되어 있는 실행중인 서비스 컨테이너를 모두 정지 후 삭제

4. ps

모든 서비스 컨테이너 목록을 조회할 때 사용
