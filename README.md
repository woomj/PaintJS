# PaintJS

바닐라 자바스크립트로 그림판 만들기
(Convas API 사용)

1. setup

    기본적인 화면 제작
    컨버스 세팅, 컬러 세팅
    reset CSS 추가

2. canvas event

    컨버스 위에 fill과 save 버튼추가
    range바 추가(크기조절)

3. 2D context

    마우스 위치에 path 생성
    위치를 따라다니며 마우스 이벤트를 받아서 좌표에 표시

4. changing color

    아래 컬러 선택 시 스케치되는 색상 변경

5. brush size / mode change

    range바를 통해 브러쉬의 사이즈를 조정
    fill모드와 paint 모드를 전환하는 버튼 설정

6. fill mode

    fill 모드 활성화 상태에서 클릭할 시 컨버스 크기만큼
    사각형으로 채워서 전체 화면을 지정 색깔로 채움

7. save image

    컨버스에 그린 그림을 기본형태인 png파일로 저장
    컨버스에서 마우스 우클릭 사용 불가능하게 변경
