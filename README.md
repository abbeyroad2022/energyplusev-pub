# Energy Plus EV 운영 퍼블리싱

# gulp 통합세팅
--------------

## Initial Setup
1. node.js 설치                          : [node.js]https://nodejs.org/en/download/
2. gulp-cli 터미널 설치                   : npm install -g gulp-cli
- 회사 방화벽 / 프록시 인증서 오류
  npm config set strict-ssl false
3. package.json(node module) 터미널 설치  : npm install
4. gulpfile.js 작업환경 터널 실행          : gulp 실행


## "gulpfile.js" 기능 및 실행방법(터미널실행)
* sass 통합,
* sourcemaps생성
* 이미지 최적화 지원
* Babel ES6

1. 상단 내용 실행, 실시간 내용 실행 브라우저 싱크. (gulp)

## Notes
<blockquote>
    "src폴더"는 작업용폴더 이고 'dist'는 배포폴더입니다.
</blockquote>

## git
- https://github.com/abbeyroad2022/energyplusev-pub

## local
- `gulp`
- http://localhost:3000/coding_list/

## deploy
- `npm run deploy`
- https://abbeyroad2022.github.io/energyplusev-pub/coding_list