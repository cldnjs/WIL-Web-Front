# vertical-align의 특성

* __vertical-align 속성의 특징__
    1. inline이나 inline-block요소에만 적용이 된다. -> block요소(ex)div태그)에는 적용 안됨
    2. 요소 자체만을 정렬, 내용에는 영향을 미치지 않는다.
    3. tale-cell에 적용할 때는 내용에 영향을 미친다.
    4. vertical-align은 정렬하려는 요소를 다른 인라인 요소에 상대적으로 정렬한다.<br>
그래서 같은 줄에서 인라인 요소의 크기에 따라서도 달라질 수 있다.<br>
그 줄에 있는 inline-height 설정에 따라서도 바뀔 수 있다.

* __인라인 요소의 속성값__
    1. baseline: 기본값, __부모 요소의 기준 선__에 맞춘다.
    1. sub: 부모의 __아래점자 기준선__에 맞춤
    1. super: 부모의 __위첨자 기준선__에 맞춤
    1. text-top: 요소의 __맨 위를 부모 font 맨 위의 맞춤__
    1. text-bottom: 요소의 __맨 아래를 부모 font의 맨 아래에 맞춤__
    1. middle: __부모요소의 중앙위치__에 맞춤
    1. top: 요소의 맨 위를 줄에서 가장 큰 요소의 __맨 위에 맞춤__
    1. bottom: 요소의 맨 아래를 줄에서 __가장 낮은 요소에 맞춤__
    1. 길이값: px, cm등으로 __0px은 baseline과 같은 값__
    1. %: line-height의 백분율, __0%는 baseline과 같은 값__