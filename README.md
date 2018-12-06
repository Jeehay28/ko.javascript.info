# The JavaScript Tutorial

이 저장소는 [https://javascript.info](https://javascript.info)에 배포된 Mordern JavaScript Tutorial의 문서를 담고 있습니다. 

| Language | Github | Translation leads | Translated (%) | Published |
|----------|--------|-------------------|-----------------|-----------|
| Chinese | https://github.com/xitu/javascript-tutorial-zh | @leviding | ![](http://translate-hook.javascript.info/stats/zh.svg?1) | https://zh.javascript.info |
| Japanese | https://github.com/KenjiI/javascript-tutorial-ja | @KenjiI | ![](http://translate-hook.javascript.info/stats/ja.svg?1) | https://ja.javascript.info |
| Romanian | https://github.com/lighthousand/javascript-tutorial-ro | @lighthousand | started | - |
| Russian | https://github.com/iliakan/javascript-tutorial-ru | @iliakan | * | https://learn.javascript.ru |
| Turkish | https://github.com/sahinyanlik/javascript-tutorial-tr | @sahinyanlik | ![](http://translate-hook.javascript.info/stats/tr.svg?1) | - |

## 한국어 번역 

현재 번역이 진행되고 있습니다. 아무나 번역에 참여할 수 있으며 언제라도 함께하고 싶다면 환영합니다.


번역에 참여하고 싶다면 먼저 이슈를 확인하여 번역이 혹시 진행 중인지 파악한 뒤에 파일명 또는 해당 article의 소제목 등 자신이 번역할 부분을 미리 등록해 주시기 바랍니다.
이슈를 확인할 때에는 close 된 이슈도 꼭 확인해 주세요. 이슈 등록 후 완료된 번역은 close 됩니다.


이렇게 함으로써 중복으로 번역하는 수고를 덜고자 합니다. 변역 완료 후 pull request 주시면 이른 시일 내에 확인하여 commit 하겠습니다. 번역이 30% 이상 완료되면 [메인 저장소](https://javascript.info)에 추가 요청할 예정입니다.

번역 시에는 마크다운 문법이 가능한 에디터를 사용하시기 바랍니다. 실제 사이트에서 어떻게 보일지 확인하고 싶다면 또는 사이트 서버를 로컬에서 실행시켜보고 싶다면 <https://github.com/iliakan/javascript-tutorial-server> 여기를 확인해 보시기 바랍니다.

## 이슈 등록 양식

아래는 권고사항으로 반드시 이렇게 하실 필요는 없습니다. 

 - 파일 위치(또는 파일 위치와 함께 번역할 파트 소제목)
 - 완료 기간 : 번역이 완료되는 기간입니다.
 
다른 이슈도 얼마든지 등록 가능합니다.

## 번역 컨벤션

 - 경어체를 사용합니다.
 
 현재 용어가 다음과 같이 번역되었습니다. 어디까지나 개인적인 의견이니 추가적인 의견이 있으시다면 이슈로 남겨주시기 바랍니다.
 
 - prototype -> 원형 (단, 코드상의 prototype은 그대로 prototype으로 표기)
 - prototypal inheritance -> 원형 상속
 - method -> 메소드
 
## 구조

모든 챕터, 기사 또는 문제는 해당 폴더를 각각 가집니다.
`N-url`식으로 명명된 폴더에서 `N`은 이후 정렬목적으로 사용되며 `url`은 URL뒤에 쓰여질 자료의 제목입니다.  
자료의 형태는 폴더 안에 파일명으로 정의됩니다.  

 - `index.md` 챕터를 의미합니다.
 - `article.md` 기사를 의미합니다.
 - `task.md` 의미합니다. (해답은 `solution.md`파일 안에 제공됩니다.)

각 파일은 `#` 마크다운 요소부터 시작합니다. 
