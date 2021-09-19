#Fastcampus Site
## Contributor
- @bokjk

## Tech Requirment (Tech Stack)
- Create-next-app
- Next.js
- TypeScript
- ES lint
- Babel 설정 (IE 11 대응)

## Docker
```
- Dockerfile 을 이용해서 Docker Container
- Docker Compose를 사용하고있음
```

```
$ docker build . -t fastcampus-size
$ docker run -p 3000:3000 fastcampus-size
```

## Script
```
$ npm run dev
```

```
$ npm run build
$ npm run deploy
```


## eslint 설정
### eslint-config-airbnb-typescript 
- 설치 https://www.npmjs.com/package/eslint-config-airbnb-typescript
- npm install eslint-config-airbnb-typescript @typescript-eslint/eslint-plugin@^4.29.3 @typescript-eslint/parser@^4.29.3 --save-dev


## 테스트
- JEST
- npm run test
