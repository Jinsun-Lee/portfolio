#### 템플릿 수정 방법
- 템플릿 깃허브: https://github.com/sjoleee/very-simple-portfolio
- 개발자 사이트: https://www.sjoleee.info
<br/>

1. 클론한 레포지토리를 `portfolio`로 만들고, `public`으로 설정
2. 사용을 위한 세팅
```
npm install
cd portfolio
npm run dev
```
3. 내용 수정
```
자동화 시스템 개발자
https://github.com/Jinsun-Lee/portfolio/blob/main/src/components/Information/index.tsx

그 밑에 소개
https://github.com/Jinsun-Lee/portfolio/blob/main/public/markdown/information/introduce.md

workExperience 상세 내용
https://github.com/sjoleee/very-simple-portfolio/tree/main/public/markdown/workExperience

workExperience 네모 이미지
[id].png만 가능하며, 120px 이상의 정방형 이미지를 권장함
https://github.com/sjoleee/very-simple-portfolio/tree/main/public/images/workExperience

그 밑에 내용
https://github.com/Jinsun-Lee/portfolio/blob/main/data.json

프로젝트 상세 + 이미지도 추가 가
https://github.com/Jinsun-Lee/portfolio/tree/main/public/images/project

data.json에서 id 삭제 금지!!!
description은 \n으로 줄바꿈
isTeam의 값에 따라서 팀 프로젝트와 개인 프로젝트 각각 나뉘어 보여짐
"webUrl": "https://github.com/sjoleee/", // 없으면 제거
"repoUrl": "https://github.com/sjoleee/", // 깃허브 레포지토리 링크니 없으면 제거!
```
4. 색상 변경
```
https://github.com/Jinsun-Lee/portfolio/blob/main/tailwind.config.js
https://www.color-hex.com/color/3d85c6

PRIMARY_LIGHT
PRIMARY
PRIMARY_HEAVY
GRADIENT_FROM
GRADIENT_TO
```
5. SEO를 향상
```
https://github.com/Jinsun-Lee/portfolio/blob/main/src/pages/_app.tsx
```
6. Vercel 배포
```
https://vercel.com/new 에서 github으로 로그인
포트폴리오 레포지토리를 선택하여 배포
```   
