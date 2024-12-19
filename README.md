# 환경변수 .env

최상위 폴더에 .env파일만들기 \
REACT_APP_API_TMDB_KEY="API_KEY" \
주의 맨뒤에 세미콜론 쓰지 않음

## .gitigonre 파일에 깃에 올리지 말아야 할것들 .env 작성


## APIKEY 사용
    const APIKEY=process.env.REACT_APP_API_TMDB_KEY;

### 깃배포하기

package.json 수정하기\
하단에  "homepage": "https://cjh7652.github.io/tmdbmovie1" 깃허브 홈페이지 주소 \
(https://cjh7652.github.io/tmdbmovie1)\


scripts 수정\
 "predeploy": "npm run build", \
  "deploy": "gh-pages -d build"\

깃저장소 업로드


###  터미널에서 gh-pages 설치하기

npm install gh-pages \


### 깃허브 저장소 다시 확인하기
git remote -v \





### 깃허브 배포하기
npm run deploy

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

