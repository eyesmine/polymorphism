# polymorphism
다형성

객체지향에서 다형성이란? 
쉽게 설명을 하면, 여러가지하는 일들을 한 가지 일로 바꾸는 것이다.

예를 들어서 "먹는다" 라는 동사가 있다고 할때..

여기서 파생되는 먹는다는 수 없이 많다.
아침을 먹는다. 점심을 먹는다. 저녁을 먹는다. 회를 먹는다. 술을 먹는다. 음료수를 먹는다 등으로 나타낼수 있을 것이다. 

이걸 코드로 옮긴다고 하면, 수 없이 많은 먹는다라는 함수가 생기게 될것이다.
객체지향을 왜 쓰는걸까? 그렇다 코드의 중복을 제거 하려고, 객체지향을 쓴다.

그렇다면 객체지향을 쓰지 않고 개발 하면 왜 안되는가?
라인바이 라인 형식으로 개발을 할 경우에는 코드량도 늘어나고, 혹시나 다음에 유지보수를 하게 될때, 찾는데 어려움과 수정하는데 어려움이 존재 할 것이다.

자 그러면 다시 다형성으로 돌아와 보자
저 위에 먹는다 라는 행위를 객체지향에서 다형성이라는 개념을 이용하면, "먹는다" 행위 하나로 끝낼수 있다.

무슨 말인가? "먹는다" 라는 행위를 인터페이스로 선언을 하고..
인터페이스를 상속받는곳에서 무엇을 먹는지 주입만 시켜주면 된다.

그러면 무엇을 먹는지에 대한게 하나로 끝난다.
이렇게 다형성은 많은 코드의 양을 줄여주는데, 엄청난 도움을 준다.




