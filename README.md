### 중요한 공지
 
📡문제집 풀이 집단 지성 프로젝트📡를 진행중입니다. [링크](docs/solution-request.md)를 참고해주세요.

질문을 하기 전 [이 글](docs/how-to-ask.md)을 꼭 참고해주세요.

---
 
# 🐕 바킹독의 실전 알고리즘 🐕

## 설명

이 강좌는 **실전성**에 가장 큰 의미를 둔 C++ 언어 기반 실전 알고리즘 강좌입니다. 청자가 C/C++ 문법은 알고 있지만 자료구조와 알고리즘에 대한 선수 지식이 없다는 가정하에 커리큘럼을 구성했습니다. 

주 타겟은 코딩테스트를 대비하는 대학생/취업준비생이지만 정보올림피아드/USACO/코드잼 등의 알고리즘 대회를 준비하고자 하는 분들도 이 강좌를 통해 대회에 필요한 기본기를 익힐 수 있습니다.

강좌는 주제에 대한 이론을 익히고 [백준 온라인 저지](https://www.acmicpc.net/)에 있는 관련 문제를 풀이하는 방식으로 진행됩니다.

개인차는 있겠지만 1주일에 40시간 이상 투자할 수 있다고 할 때 완강까지 2-4개월 정도 걸립니다. 완강을 한다면 앞으로 코딩테스트에서 애를 먹을 일은 절대 없을 것이고 일정상 완강을 할 수 없는 상황이라면 `0x11강 - 그리디`까지만 익히고 코딩테스트에 임해도 충분히 승산이 있습니다.

## 강의의 장점

1. 강의자가 알고리즘을 많이 잘하고 경험이 풍부합니다🤣(OJ 2000+ solve, 코드포스 레이팅 2400+, KOI/ICPC/SCPC/카카오 코드 페스티벌 수상 등). 수년간 강의자가 몸으로 부딪치며 쌓아온 경험을 바탕으로 고수의 시각에서 문제에 접근하고 이해한 내용을 바탕으로 실전적인 코드를 작성하는 요령을 강의에 잘 녹여냈습니다.

2. 처음 강의를 시작한 때로부터 지금까지 3년이 넘는 시간동안 블로그와 유튜브를 통해 모두에게 공개되어 피드백을 계속 받아왔기 때문에 강의 내용과 코드의 오류가 적고, 리뉴얼을 통해 보다 더 자세하고 초보자에게 친절한 강의가 되게끔 내용을 작성했습니다.

3. 백준 온라인 저지를 통해 연습 문제를 제공합니다. 그리고 강의에서 같이 다룬 80여개의 문제 이외에도 주제별로 문제 목록을 기본 문제/응용 문제로 분류해서 제공하고 풀이를 모아두었기 때문에 강의를 듣고난 후 문제를 풀며 학습을 할 수 있습니다.

## FAQ

### C언어는 알고 있는데 C++을 몰라요. C++을 먼저 배우고 올까요?
C언어는 알고 있는데 C++을 잘 모른다고 하면 강의를 따라오는데 큰 문제가 없습니다. 강의에서 다소 생소할 수 있는 C++문법들에 대해서는 설명을 해두었기 때문에 굳이 C++을 마스터하고 이 강의를 들으려고 하기 보다는 강의와 함께 C++ 공부도 병행하면 됩니다.

### C++ 대신 자바/파이썬만 아는데 강의를 들어도 괜찮을까요?
코딩테스트 언어 선택에 대한 제 생각은 [이 글](https://blog.encrypted.gg/965)을 참고해주세요. 강의에서 효율적인 구현은 이론 못지않게 큰 부분을 담당하고 있습니다. 추후에 자바/파이썬 버전을 제작할 생각이 아주 약간 있긴 하지만 기약이 없고 현재로서는 모든 구현이 C++으로 제공되기 때문에 시간이 여유롭다면 주 언어를 C++로 변경하는 것을 추천드립니다.

꼭 자바/파이썬으로 코딩테스트를 치려고 한다면 당장은 달리 방법이 없습니다. 그래도 C/C++에 특화된 구현을 제외한 나머지 내용은 언어와 크게 상관이 없으니 일단 강의를 한 번 보고, 도저히 안되겠다 싶으면 제 강의 대신 코딩테스트를 치고자 하는 언어에 특화된 강의를 찾아서 보시면 됩니다.

### 슬라이드나 기타 강의 자료를 개인 블로그에 복습용으로 올려도 되나요?
비상업적 & 출처 표시 조건 하에 가능합니다.

### 강의를 꼭 순서대로 들어야 하나요?
강의의 배치는 난이도순입니다. 또한 마치 선수과목과 같이 앞쪽 강의를 들어야 뒷쪽 강의를 이해할 수 있는 경우가 있어서(ex : 스택 -> 스택의 활용, 재귀 -> 백트래킹, 재귀 -> 정렬 I 등등) 가능하면 순서대로 듣는 것을 추천드립니다.

부득이하게 뒷쪽 강의를 먼저 들어야 하는 상황이라면, 듣다보면 앞쪽에서 필요한 개념이 무엇인지 감이 올텐데 그걸 참고해서 필요한 앞쪽 강의만 찾아서 들으시면 됩니다.

### 질문은 어디에 하면 되나요?
다른 사람도 질문을 참고할 수 있게 해당 강의 블로그 글 or 동영상에 댓글로 달아주세요. 개인적인 질문은 admin [at] encrypted.gg 메일로 보내주시면 됩니다. 질문을 하기 전 [이 글](docs/how-to-ask.md)을 꼭 참고해주세요.

## 리뉴얼 예상 목차
```
0x00강 - 오리엔테이션
0x01강 - 기초 코드 작성 요령 I
0x02강 - 기초 코드 작성 요령 II
0x03강 - 배열
0x04강 - 연결 리스트
0x05강 - 스택
0x06강 - 큐
0x07강 - 덱
0x08강 - 스택의 활용(수식의 괄호 쌍)
0x09강 - BFS
0x0A강 - DFS
0x0B강 - 재귀
0x0C강 - 백트래킹
0x0D강 - 시뮬레이션
0x0E강 - 정렬 I
0x0F강 - 정렬 II
0x10강 - 다이나믹 프로그래밍
0x11강 - 그리디
0x12강 - 수학
0x13강 - 이분탐색
0x14강 - 투 포인터
0x15강 - 해시
0x16강 - 이진 검색 트리
0x17강 - 우선순위 큐
0x18강 - 그래프
0x19강 - 트리
0x1A강 - 위상정렬
0x1B강 - 최소 신장 트리
0x1C강 - 플로이드 알고리즘
0x1D강 - 다익스트라 알고리즘
0x1E강 - KMP 알고리즘 
0x1F강 - 트라이
부록 1 - 동적 배열
부록 2 - 비트마스킹
부록 3 - Union Find
부록 4 - 다이나믹 프로그래밍 심화
```

## External Links

- [실전 알고리즘 강좌 블로그](https://blog.encrypted.gg/category/%EA%B0%95%EC%A2%8C/%EC%8B%A4%EC%A0%84%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)
- [유튜브](https://www.youtube.com/c/baaarkingdog)
- [깃헙 리포지토리](https://github.com/encrypted-def/basic-algo-lecture)
- [문제집 링크](workbook.md)
- 메일 주소 : admin [at] encrypted.gg
 
