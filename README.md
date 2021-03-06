# 프로젝트<br>

### 세계 국기 퀴즈<br>

국기 이미지를 보고 국가 이름을 맞추는 미니 퀴즈 게임<br>
firebase url : http://vue2-country-quiz.web.app/ <br>
** https, http 혼합된 컨텐츠 문제 해결이 완벽히 되지 않아 크롬 웹브라우저에서 오픈 요망<br>
** 임시방편: 퀴즈 화면 주소창 맨 앞에 자물쇠 모양 혹은 주의요함 클릭 -> 사이트 설정 클릭 -> 안전하지 않은 콘텐츠 '허용' 선택해야 잘 동작<br>

<img width="945" alt="스크린샷 2022-02-14 오후 2 00 44" src="https://user-images.githubusercontent.com/62632252/154015512-305f359f-0295-4d3f-9321-4bfea8ddf1ec.png">

# Skills

1. database : 공공데이터 Open Api
2. js framework : Vue.js
3. style : SCSS
4. ui framework : Element ui
5. hosting : firebase

# 주요 기능

1. 오픈 api에서 받아온 데이터로 국기 이미지 랜덤 출력
2. 정답/오답 체크 및 결과 저장 후 출력

![Feb-14-2022 16-51-05](https://user-images.githubusercontent.com/62632252/154015468-d4d12e54-0ab6-400a-a488-a4e00fadc543.gif)
![Feb-14-2022 17-34-53](https://user-images.githubusercontent.com/62632252/154015485-799c59f7-aa6d-4ea0-9bf5-dd4fec1ca4e6.gif)

# 스타일
1. 퀴즈에 알맞게 고딕종류보다 살짝 둥근 Godo font 사용
2. 힌트 보는 부분은 간단한 css 애니메이션 구현
3. 퀴즈 화면의 NEXT, HOME버튼 툴팁 제공 (모바일 제공 X)
4. 반응형으로 제작

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
