# 41615063
##전역변수
1.x:방울이 그려질 픽셀의 너비 
2.y: 방울이 그려질 픽셀의 높이 값
3.z: 방울의 반지름 값 (1~100사이의 랜덤)
    
##그리기 버튼을 클릭
+타이머 활성화

##타이머 작동 시
1.방울의 위치: 전역변수 x,y
2.방울의 크기: 전역변수 z
3.방울의 채우기 여부: 참(YES)
4.방울의 색깔:
+R(0~255)
+G(0~255)
+B(0~255)
5.방울이 그려질 때 소리(beeps16.mp3)도 출력

##지우기 버튼 클릭
1.타이머 비활성화
2.캔버스 초기화 (방울이 지워짐)
3.소리 출력 정지
