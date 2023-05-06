Box model과 FLEX Box

모든것은 "박스"다
​
콘텐츠-패딩-보더-마진

박스의 테두리 border


1. 블록 레벨 요소

한 줄을 차지하는 박스

2. 인라인 레벨 요소

자신만을 감싸는 박스


패딩
콘텐츠와 border 사이의 간격
​

마진
border로 부터 다른 콘텐츠 사이의 여백
​

top -> right -> bottom -> left
ex)
margin: 10px 30px 0 20px;
margin: 10px 30px;     //위아래는 10px, 좌우는 30px
​

Flexbox Layout
​
아이템이 배열될 방향인 '주축'을 정할 수 있다.

justify-content : main axis
align-items : cross axis
저주 콘서트
크로스-라인
​
mian axis -> row
main axis -> column
​

column-reverse 또는 row-reverse를 사용하면 요소들의 start와 end의 순서도 뒤바뀐다.

Flex의 방향이 column일 경우 justify-content의 방향이 세로로, align-items의 방향이 가로로 바뀐다.

flex-direction과 flex-wrap이 자주 같이 사용되기 때문에, flex-flow가 이를 대신할 수 있다.

예를 들어, 요소들을 가로선 상의 여러줄에 걸쳐 정렬하기 위해 flex-flow: row wrap을 사용할 수 있다.

​

+)
css grid layouts
can i use?