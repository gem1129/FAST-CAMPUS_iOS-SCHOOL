Day25_Block, Animation, UIScrollView
--

####:notebook: **이론**

#####**Block**
- 무명함수의 역할을 하는 객체
- iOS 프레임워크에 기본적으로 구축되어있지만 사용자마다 다른 행동(함수)을 할 수있는 곳에 사용됨
- 델리게이트와 비슷한 역할을 하지만 델리게이트에 비해 가독성이 뛰어나고, 코드 복잡도가 낮음
- 비동시성 작업에 많이 사용됨(일의 순서와 상관없이 작업이 진행됨)
- 자체적으로 스레드를 생성해 작업을 하기 때문에 스레드 관리가 어려움
- ex) UIView Animation, UIAlertController

<br>
- ****
- 
####:computer: **실습**
- UIScrollView 생성 
- Animation 효과 설정 및 block 함수 이용