inner display type
- 박스 내부의 요소들 배치를 결정

# flexbox
행과 열로 배치, 1차원 레이아웃 방식
'공간 배열' & '정렬'
간접적으로 이동시킴

네 방향
행 오 외
열 위 아래

외부의 큰 박스 기준으로 내부의 요소 컨트롤

## 구성요소
1. flex container
주체
부모 태그, 
display: flex or inline-flex로 설정된 부모 요소

2. flex items
- 콘테이너 안에 들어가는 요소

3. main, cross axis
- 무설정: 메인축은 왼쪾 가로로 정렬, 
        위부터 쌓인다.
    - main axis(주 축)
        main start-> main end(기본값)

## 속성
부모용
display, flex-direction, flex-wrap, justify-content
부모의 힘으로 큰틀의 정렬이 가능

지정:`display: flex;`

아이템에 주는 용

### 배치에 대한 큰그림
- flex-direction
- flex-wrap

### 공간 분배
- justify-content 주축
- align-content 교차죽

### 정렬
- align-items 한 줄
- align-self 한 개


justify 속성이 많이 없는 이유
=> 필요 없기 때문
=> margin auto를 통해 정렬 및 배치가 가능


## 나머지
flex-glow 남는 자리 분배