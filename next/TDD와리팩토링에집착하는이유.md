## TDD와 리팩토링에 집착하는 이유
모든 프로그래밍을 TDD를 하시나요? 아니요 그렇지는 않은데요! 백퍼센트 TDD를 하는건 아닌데요
재성님은 삶 자체를 TDD로 사는것 같은데, 이럴 의도는 아닌데, TDD와 리팩토링에 집착하는 이유를 
영향을 미친 이유가 있기 때문에 어떤 과정을 학습할때 좋은 방법을 설명

- TDD(Test Driven Development)
- 켄트백이 말함

- TDD란 프로그래밍 의사결정과 피드백 사이의 간극을 의식하고 이를 제어하는 기술이다
- TDD의 아이러니 중 하나는 테스트 기술이 아니라는 점이다.
- TDD는 분석 기술이며 설계 기술이다.

- 핑퐁을 주면서 설계를 만들어가는것
- TDD로 프로그래밍을 할때 분석이나 설계를 안해도된다고 하는데
- 분석을 안하면 오히려 TDD를 하기 힘들다.
- 분석을 안하고 막개발 하려면 힘들다.
- 처음에 요구사항 분석을 잘해야한다.
- 설계를 해야한다 거창한게 아니라 대략적인 설계를 무조건 해야한다.

- TDD = Test First Development + 리팩토링

- 실패하는 테스트를 먼저 만듬, 배포해야하는 코드를 먼저 만드는게 아니다.
- 컴파일 에러가 생긴다. 테스트를 패스하고 리팩토링 후 테스트 실패로 다시 돌아간다.

- 테스트 우선개발 , 리팩토링이랑 합쳐진것이다.
- 프로덕션코드를 먼저 생각하는데 + 리팩토링이다.
- 테스트 기반으로 해서 개발 방식이라고 해서 드리븐 디벨롭먼트이다.
- 중요한건 리팩토링이다. 리팩토링은 설계이다.
- 앞단계에서 러프하게 설계를 하고 짧은 단계의 설계를 지속하는 방식이다.
- 핑퐁처럼 주고받으면서 짧게 할수 있다.
- 왔다갔다 하면서 하는게 재밌다 성취감도 생긴다.

- TDD와 리팩토링에 집착을 하냐

#### 나는 사람이다.
- 백엔드 개발자로 살면서 많은 회사에 있으면서 장애가 있을까봐 두려워서
- 장애대응 해야하고 그러는데, 앞으로 그래야한다.
- 요구사항 추가, 변경 때문에 소스코드를 수정하고 불안감에 살고 싶지 않다.
- 코드배포하고 신께 기도하고 내가 만든 코드에 자신감을 가지고 싶다.

#### 나는 평범하다.
- 한번에 하나만 집중할 수 있다.
- 우리들이 개발을 할때 보면 새로운 기능을 추가하거나 새로운 문제를 접하게 되면
- 설계고 나발이고 빠르게 구현하는거에 집중을 한다.
- 그 뒤에 설계에 집중이 된다. 
- 어떤 개발자는 구현과 설계에 같이 하는 경우가 있다.

- 구현에 집중
    - 실패하는 테스트 -> 테스트 성공
        - 로직을 구현하는 것에 집중
        - 테스트를 통과하기 위해 어떠한 행위도 허용
        - 마음의 안정을 느낄수 있다.
        - 심적으로 안정이 되어야지 뇌가 말랑말랑 해진다.
        - 창의적으로 활동하려면 조급함이 있으면 안됨
- 설계에 집중
    - 리팩토링
        - 메소드 클래스 설계
        - 클린코드 구현
        - 새로운 테스트 케이스가 추가되도 안된다.
        - 한번에 한가지만 고민을 해도 된다.

- 테스트가 있기 때문에 리팩토링을 할수 있다.
- 구현을 끝낸뒤에 커밋을 한다. 원상복귀를 한다. 리팩토링을 한다.
- 테스트 코드를 통해 구현을 할수 있따.


#### 나는 프로그래머이다.
- 내가 구현하는 코드에 자부심을 느끼고 싶다.
- 일정이 빨리빨리 하에 코드가 쓰레기가 되어가는데 개발에 대해서 전문가가 되어야한다.
- 프로그래밍은 정말 재밌는 일이다.
- 단순반복 의미 없는것만 활동을 하다보니까 직업 자체에 대한 만족도가 떨어진다.
- 만족도를 높이는 강점은 리팩토링이라고 생각한다.
- 프로그래머로서의 즐거움을 느낄수 있다.
- 프로그래밍을 아트라는 영역에 대해
- 리팩토링은 창의적인 영역이며 아트의 영역이다.
- 이 활동을 많이 해야지 프로그래머로서의 자부심을 느낀다.
- 리팩토링만 할수는 없다. 1시간 30분만이라도 이런 활동만 하면 재밌는 일을 했기 때문에 자부심을 느낄수가 있다.

#### TDD 리팩토링을 삶에 응용하기
애자일과 관련이 있다. 애자일의 한 프랙틱스가 TDD이다.

- 책쓰기
    - 현재 상태에 쓸수 있는 내용위주로 빠르게 챕터를 마무리
    - 챕터를 마무리 했으므로 이너피스
    - 챕터를 마무리 한 후 편집자 또는 주변 친구들에게 공유해 피드백한다.
    - 피드백을 받아 챕터별 퇴고(리팩토링)
    - 모든 챕터를 마무리하고 2차퇴고
    - 마음에 들때까지 무한루프
- 회사다니면서 창업
    - 측정 가능한 가설을 세운다
    - 구현을 통해 소비자에게 피드백한다
    - 개선한다
    - 측정 가능한 가설을 세운다
    
#### TDD 리팩토링의 핵심
- 큰 단위를 작은단위로 나눠 빠르게 실패
- 피드백을 통해 지속적으로 개선
- 달성하기 힘들것으로 생각하는 일에 도전할 수 있는 용기

- 요구사항 분석을 잘 해야하지만 잘 설계를 잘하고
- 작은단위로 잘 나눌수 있다.

만족스럽다고 하면 삶에도 적용할 수가 있다.


#### 일반인과 성공하는 사람의 시각차이
- 평범한 사람은
    - 한방을 좋아한다
- 성공하는 사람은
    - 작은단위로 쪼개서 가설을 세우고 실패하고 문제점을 세우고 해보고 실패하고 성공한다.
- 성공하는 스타트업은 실패 2번정도 해본사람이 성공하더라


#### 커네빈 프레임워크 - 인과관계의 불확실성에 따라 문제상황
- 4가지 문제
    - Simple: 단순성 영역
        - 모범 사례를 통해 문제 해결, 조립 설명서
    - Complicated : 난해성 영역
        - 기존의 전문 지식을 활용해 문제해결 가능
    - Complex : 복잡성 영역
        - 새로운 해법을 제시
    - Chaotic :혼돈 영역
        - 불명확한 상태에서 살아남기 위한 방법을 찾아 대응한다.
        

앞으로 해결해야할 상당히 많은 문제는 명확하게 문제가 정의되어 있지 않거나 분석할 데이터도 없기 때문에 기존의 접근 방식으로
해결하기 힘든 Complex(복잡성) 영역이다.

지금 필요한 것은 새로운 문제 해결 접근방식에 도전할 수 있는 용기

