학습목표
flexbox에 대해 알아보자
규칙1
flexbox 자식을 원하는대로 움직이게 하기 위해서는
기본적으로 부모요소에 명시를 한다.
즉, flexbox-container로 만들어주면 된다.

규칙2
주축(main axis), 교차축(cross axis)이 있다.
justify-content, justify(현재 방향의 주축을 담당하는 속성)
align-items(교차축을 담당하는 속성)

기본적으로 주축은 수평, 교차축은 수직이다.
하지만 default이기 때문에 변경될 수있다.
100vh(vieport Height)(스크린마다 다름)