#Clone Talk

'카카오톡' 채팅앱 화면 구현
js나 db는 사용하지 않고 레이아웃 및 디자인 연습용 


B.E.M.(Block Element M)
:클래스명을 지정하는 방법 중 하나

블럭에 클래스명 지정
블럭의 구성요소 __로 클래스명 지정
구성요소의 속성 --로 클래스명 지정

Ex.)
  <div class="borad">
    <h1 class="borad__title">제목</h1>
    <p class="borad__content">내용</p>
    <input class="borad__btn" type="button" value="버튼">
    <input class="borad__btn--big" type="button" value="큰버튼">
    <input class="borad__btn--big borad__btn--yellow" type="button" value="크고 노란 버튼">
  </div>

  ※장점
  1. 타인이 혹은 미래에 보더라도 class명만으로 해당 태그의 역할을 쉽게 짐작할 수 있다.(협동성/연속성/신속성)
  2. 정해진 규칙이 있으므로 변수명 지정에 드는 고민을 줄일 수 있다.(시간비용 절감)
  3. css selector를 위해 class만을 사용하므로 html을 참고 수가 줄어든다.(편리성)

  ※
  1. class명이 길어짐에 따라 난잡해 보일 수 있다.(미관 저하)
  2. class명 지정에 사용할 단어선택의 차이 부분은 해결하지 못함 Ex.) content? text?
