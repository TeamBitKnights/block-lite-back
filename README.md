# block-lite-back

## 설명

이 프로젝트는 EVM 체인에서 작동하는 오픈소스 블록 탐색기입니다. 이 저장소를 사용하면 로컬에서 탐색기를 실행할 수 있으며, 백엔드 코드를 제공합니다. 이 서버는 RESTful API를 통해 데이터베이스에 접근하여 데이터를 가져옵니다.

## 시작하기

### 설치 방법

- 크롤링 서버를 아직 구축하지 않았다면, 아래 링크를 먼저 따라 설정을 완료하세요.

  - <https://github.com/TeamOliveCode/block-lite-crawler>

- 이 저장소를 Git 클론하세요.

```bash
https://github.com/TeamOliveCode/block-lite-back.git
```

- MySQL 데이터베이스 설정을 업데이트하기 위해 `.env` 파일을 생성하세요.

```env
DB_HOST="host"
DB_USER="user"
DB_PASSWORD="password"
DB_DATABASE="explorer_db"
```

- 아래 명령어를 사용해 로컬에서 실행하세요.

```bash
npm install --save
node server.js
```
