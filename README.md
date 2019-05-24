# SIT32002-HCI-4조 리듬손타
LeapMotion을 활용한 지휘 프로그램
[Leap Motion과 스크레치 사진 넣기]


Members

  * 21300207 김태운 / 21500431 유재은 / 21600202 나누리

Agenda


Purposes / Expectation

  * 리듬손타 프로그램은 교육용 프로그램으로서, 음악을 학습하는 학습자를 대상으로 지휘법을 배우고, 직접 실습할 수 있도록 하는 프로그램이다. 
    사용자는 이로 하여금 지휘법을 익히고 음악적 이해도를 높이는 데 그 의의가 있다. 
    기존과는 다른 색다른 학습법의 도입으로, 쉽고 재미있게 지휘법을 익힐 수 있을것이다. 
    또한, 그에 따라 음악을 좀 더 풍부하게 이해할 수 있을 것이라 생각된다.

  
details
------------------------


Photos & videos
----------------------
![prototyping](https://user-images.githubusercontent.com/42803425/57272681-ab8a0080-70cf-11e9-8839-8f9fc9430d39.png)



# 구현방법: 
Leap Motion ver. 2.3.1 과 ScratchX를 활용하여 제작 Background & objective of research
------------------------


1. 구동환경 구현

https://www.leapmotion.com/setup/desktop/ 
http://scratchx.org/?url=http://khanning.github.io/scratch-leapmotion-extension/examples/Leap%20Motion%20Example%20-%20Hand%20Skeleton.sbx#scratch
(해당 페이지에서 Windows, Mac, Linux 등 버전에 맞게 다운로드 가능)


2. 구현원리

  * Leap Motion Controller는 컴퓨터와 USB를 활용, 연결시켜 사용하는 기기이다.
  
  * 기기에 내장과 LED와 카메라 센서를 통해 움직임을 인식하여 화면으로 반영한다.
  
    기기에서 8-cubic feet (2x2x2) 정도 떨어진 공간을 개략적으로 스캔하며, Leap Motion 기기는 양 손과, 10개 손가락을 모두 추적할 수 있다.
    
  * Interaction 예)
    - 손을 움직임이 그대로 반영되어, 움직임에 따라 자신이 움직인 궤적이 나타나도록 함.
    - 손의 움직임으로 마우스의 기능을 대체할 수 있도록 함. (2초 이상 머물면 다음 화면 전환)
    - 움직임을 점수화하여, 시각적으로 나타내도록 함.
    
    
3. 장점

 - 학습자가 직접 참여해 손과 팔을 직접 움직이며 실제 지휘법을 익힐 수 있음
 
 - ScratchX를 활용하면 비교적 손쉽게 창의적인 컨텐츠 제작가능
 
 - 빠르고 간편하게 다양한 컨텐츠의 프로토타이핑 및 그래픽 등의 검토 가능
 - 
 

4. 한계점

 - 화면 크기, 해상도, 세부 동작 등의 구현에 있어 기술적 제약 존재.
 
 - 평가 기준의 미비.


as they move through the open space between you and your computer, the special software detects your hands and fingers and translates the data into information for your computer.
ㅣ: https://www.leapmotion.com/setup/



# References
  [1] 
  [2] 
  [3] 
  ...

