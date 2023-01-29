# 3차 활동
1. Rule Tile을 이용한 맵 배치
- Unity 2D tile map extra를 설치 후 Rule Tile로 맵을 만들 수 있다.
폴더 내 이미지 RuleTile_1처럼 Inspector 창에서 각 블록마다 조건을 추가하면 RuleTile_2처럼 드래그만 해도 자동으로 타일이 설치된다.
- Rule Tile로 길을 제작했다면, WayPoint를 이용하여 적 오브젝트가 움직일 경로를 설정해 줄 수 있다.
적의 생성은
Coroutine를 이용하여 코드를 작성한다. 
Update문이 아닌 Coroutine를 이용하는 이유는 Coroutine은 필요한 순간에만 반복하는 특징이 있기 때문에 매우 효과적으로 최적화할 수 있다. (Coroutine 이미지 참고)

2. 타워 배치
- RayCast()를 이용하여 마우스가 클릭하는 위치에 타워를 생성할 수 있다.
