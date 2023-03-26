add - 작업공간에서 Staging Area로 변화들을 쌓아둔다.
commit - Staging Area에 모인 것들을 Local Repository에 저장한다.
push - Local Repository에 커밋한 내용들을 외부 저장소인 Romote Repository에 저장한다.

fetch - remote repository에 있는 정보를 확인한다. local로 가져오지는 않는다.
pull - remote repository에 있는 정보를 확인하고 복사해 가져온다.


1주차

URI : Uniform Resource Identifier
USL : Uniform Resource Location
URN : Uniform Resource Name

URL : 프로토콜 + DNS주소
IP주소의 문제점
1. 길고 복잡한 IP주소들을 위우거나 관리하기 힘들다.
2. 사정에 따라 바뀔 수도 있다.
-> DNS(Domain Name Server)의 등장

HTML : 자료
CSS : UI
JavaScript : 제어


2주차

파일의 4가지 상태
1. 추적X(Untracked)
2. 변경 X(Unmodified)
3. 변경 O(Modified)
4. Staged

작업공간(Working Directory)
Staging Area
Local Repository

add - 작업공간에 있는 파일을 Staging Area로 보냄
commit - Staging Area에 쌓여있는 내용들을 Local Repository로 보냄
-> 결국 내 컴퓨터 안이다.

push 명령어로 Remote Repository로 보냄

Remote Repository - github, bitbucket 등

fetch - remote repository에 있는 정보를 확인한다. local로 가져오지는 않는다.
pull - remote repository에 있는 정보를 확인하고 복사해 가져온다.

