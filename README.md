## Getting Started

1. .env.local.example 파일을 복사하여 .env.local 이름으로 새로 생성

   (보안상 git에서 .env를 ingnore 처리 때문에..)

2. 터미널 열고 Node 서버 올리기

```bash
npx json-server@0.17.4 --port 9999 --watch db.json
```

3. 다른 터미널 하나 더 열고 NextJs 실행

```bash
npm run dev
```

3. 브라우저 URL접속

   [http://localhost:3000](http://localhost:3000)으로 접속하여 실행확인

4. 배포시 빌드 및 빌드파일 실행 방법

```bash
npm run build # 컴파일 빌드 실행
```

빌드실행이 완료되면 아래 명령어로 실행

```bash
npm run start # 빌드완료 된걸로 실행
```
