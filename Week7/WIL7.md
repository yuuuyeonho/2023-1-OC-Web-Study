ㅇ 구획 나누기

큰 구획 먼저 나누기

 1.전체: View
 2.헤더: header
 3.헤더 외 아래 부분: container
 4.container 안에서 메인이 되는 부분: main-container
 5.사이드 부분: aside-container
 6.영상 재생부: video-container
 7.영상 게시자 정보: video-info-container
 8.영상 댓글: comment-container

일단 큰 구획을 나누고, 구획들과 안의 요소들이 어떻게 배치되어 있는지 큰 그림을 그려준다.

ㅇ CSS 초기화
각 브라우저마다 브라우저 스타일이 있다.
브라우저 스타일을 초기화 해줘서 모든 브라우저에 동일한 스타일을 적용해준다.


스타일을 적용할 style.css 파일 맨 처음에 브라우저 스타일을 초기화한 reset.css 파일을 import 해주기
@import 'reset.css';
ㄴ @import 방식은 다른 스타일 시트에서 또 다른 스타일을 가져올 때 사용한다.

ㅇ CSS
가장 위에 있게 하고 싶다면
top: 0; 속성을 가지게 해준다.
특정 위치에 붙어있게 하고 싶다면
position: sticky; 속성을 가지게 해준다.

마우스를 올리면 회색으로 변하게 하기 -> hover, background-color: grey;

border-radius:  동그랗게 만들기, %(퍼센트) 조절 가능

drop-down
마우스를 올렸을 때 drop-down 나오게 하기	
.dropdown-box{
display: none;
...
}
상태에서 

dropdown:hover .dropdown-box{
    display: block;
}

-> display: block 으로 바꿔주기