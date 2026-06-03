# Docker FastAPI Course Records

## 프로젝트 소개

이 프로젝트는 오픈소스소프트웨어실습 실습 5 Docker 과제로 제작한 FastAPI 기반 REST API 서버입니다.

실습 4에서 구현한 수강기록 API를 Docker 컨테이너 환경에서 실행할 수 있도록 구성했습니다.

수강기록 데이터는 `courses.json` 파일로 관리하며, FastAPI를 통해 전체 수강기록 조회와 새로운 수강기록 추가 기능을 제공합니다.

---

## 주요 기능

1. `GET /courses`를 통한 전체 수강기록 조회
2. `POST /courses`를 통한 새로운 수강기록 추가
3. `courses.json` 파일 기반 데이터 관리
4. `Dockerfile`을 이용한 FastAPI 애플리케이션 컨테이너화
5. Docker 컨테이너 실행 및 80번 포트를 통한 외부 접속
6. `--restart always` 옵션을 이용한 컨테이너 자동 재시작 설정

---

## 파일 구성

```text
docker-fastapi-course/
├─ main.py
├─ courses.json
├─ requirements.txt
├─ Dockerfile
├─ .gitignore
└─ README.md
