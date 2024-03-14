# BOM

- 브라우저를 객체화 한 것 → 브라우저를 script 언어로 제어하기 위해

## broswer 객체

- window: 모든 객체가 소속된 객체이며, 브라우저 창을 의미. window는 생략 가능
  - `window.open(’주소’)`: 해당 주소로 새탭이 열림
  - `window.close()`: 해당 탭 닫음
  - `window.alert(’~’)`: 경고창 띄움
- document: 현재 문서(DOM)에 대한 정보를 갖고 있는 객체. dom 객체를 가져올 수 있음. window 객체에 소속된 객체지만 window 생략함
  - `document.querySelector(~)`
- history: 현재 브라우저가 접근했던 URL history를 제어할 수 있음
  - `history.back()` : 이전 페이지로 감 (= ←)
  - `history.forward()` : 앞으로 감 (= →)
- location: 문서의 주소와 관련된 객체. window 객체의 프로퍼티인 동시에 document의 프로퍼티.(window.document 생략)
  이 객체를 이용해 윈도우 문서 URL을 변경할 수 있고, 문서의 위치와 관련해서 다양한 정보를 얻을 수 있음. - `location.host` : 홈페이지의 호스트를 갖고옴 - `location.href` : 웹문서 주소 - `location.href = '주소'` 로 현재 주소 바꿀 수 있음(해당 주소로 이동)
- screen: 사용자의 디스플레이 화면에 대한 다양한 정보를 갖고 있는 객체
  - `console.log()`: 텍스트 출력 효율적
  - `console.dir()`: 객체 출력 효율적
    - `console.dir(screen)`: 사용자 디스플레이 정보 자세히 알 수 있음
- navigator: 실행중인 애플리케이션(브라우저)에 대한 정보를 알 수 있음. 크로스 브라우징 이슈를 해결할 때 사용할 수 있음(ex. Crome → addEventListener)
  - `navigator.geolocation.getCurrentPosition()` : 현재 애플리케이션에 대한 위치정보
  - `navigator.appName` : 앱(브라우저) 이름을 반환
  - `navigator.appVersion`: 앱(브라우저)에 대한 버전 정보 반환
  - `navigator.userAgent`: 서버에 요청할 때 앱(브라우저)에 대한 정보

# 참고

https://www.inflearn.com/course/%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%EB%82%A0%EA%B0%9C%EB%8B%AC%EA%B8%B0
