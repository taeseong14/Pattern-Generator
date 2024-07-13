# Pattern Generator

https://www.youtube.com/watch?v=PKjbBQ0PBCQ


오랜만에 재밌어보이는걸 찾음


### 기능

 - 기본적으로 \<canvas\> 사용
 - 처음 시작부분 드래그로 설정 가능;
 - 다른 패턴 최대 1~n개로 n(<=8)개 라인 생성 가능
 - 기본 규칙: 
     - 점은 한번씩만 사용
     - 최소 4개의 점 사용
     - 다른 순서 == 다른 패턴
     - 중간 점 건너뛰기 불가 (이미 쓰인 점은 제외)
     - [explaining vid (0:57 ~ 1:22)](https://youtu.be/PKjbBQ0PBCQ?si=8cfbrRLfaH0p3F6A&t=57)


### Todo

 * Design
     + [ ] 피그마
         - [ ] point 9 dots
         - [ ] `using dots` input 
         - [ ] `using slopes` input
         - [ ] lines list? (0, Inf., ±1, ±2, ±½)
         - [ ] Gen btn

 * Function
     - [ ] enable init with dragging
