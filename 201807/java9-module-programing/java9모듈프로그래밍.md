# 구매일
2018년 07월 23일
# 구매 계기
* java9 에 도입된 모듈 시스템 공부 필요
# 기대 효과
* 모듈 시스템에 대한 이해
* 저자의 코딩 스타일, 네이밍 방법 공부
* 꾸준한 독서 습관
# 느낀점
1. 왜 모듈 시스템이 필요한지 구체적인 사례를 들어 설명해서 이해하기 쉬웠다.
    1. 웹 개발을 주로 해서 2017 스프링모임에서 들었던 임베디드환경과 같이 시스템 리소스의 제약이 있는 경우 JRE, JDK 전체를 설치하는 것보단 필요한 모듈만 이용하는 것이 좋다는 사례는 와닿지 않았었다. 
    1. 마찬가지로 클라우드 기반 컨테이너 환경을 구성할 때 더 용량이 적게 들어서 유리하겠지만 직접 경험한 것이 아니라 이또한 와닿지 않았다.
    1. 반면 책에서 드는 구체적인 언어차원에서 캡슐화, 모듈프로그래밍을 지원하지 않을 때 발생하는 문제점에 대한 예시는 평소에도 느끼던 부분이라 더 공감이 갔다.
1. 하나의 라이브러리에서 마주할 수 있는 문제점, 배포할때의 문제점, 그리고 rt.jar의 문제점까지 점차 대상의 크기를 확대하는 방식이 인상적이였다.
1. 그동안 자바를 사용할때 하위호환성에 대한 걱정을 안해도 되서 좋아했기 때문에 java9에 많은 실망을 했었다. 
    1. 하지만 난 계속 java 를 사용할것이고, 변화를 받아들일 것이기 때문에 module 시스템을 이해하기 위해 책을 구매 했다. 
    1. 그리고 만약 내가 하위호환성을 깨야하는 상황이 오면 어떤 선택을 할 것인지 고민 하는 계기가 되었다.
1. 자바 모듈은 기존 자바 프로젝트와는 다른 폴더 구조가 필요하다.
    1. module-info.java 의 첫인상은 모듈의 정보를 정의한다는 점에서 js에서 package.json 느낌이 든다. 둘을 비교하는 것은 옳은 것일까?
1. 모듈시스템의 큰 특징은 다른 모듈이면 public 접근 제어자를 가진 클레스, method라 해도 연관 관계를 설정하지 않으면 접근할 수 없다는 것이다.
    1. Visibility(가시성)은 java9의 큰 변화다.
1. 모듈의 requires 는 모듈 단위고 exports는 패키지 단위이다.
    1. com.banbanmumani.util 패키지를 export 한 경우 com.banbanmumani.util.impl 패키지도 export 될것이라 예상했는데 그렇지 않다. 
    1. 자바의 패키지는 계층적이지 않다.
1. 모듈 시스템을 통해 좀더 캡슐화를 이를 수 있다고 느껴진다. 이제 조금 java9의 철학에 공감이 간다.

# 완독일
# 독서 평가
# [책정보](http://www.hanbit.co.kr/store/books/look.php?p_code=B7608640342)
