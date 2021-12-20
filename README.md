# OpenSource-Software Final Term Project



---



## Title

Drawing with AI virtual mouse



## Libraries

- cv2
- mediapipe
- PyQt5
- pyautogui



## Getting Started

python AIVirtualMouse.py



## References

[간단한 그림판 프로그램](https://codetorial.net/pyautogui/mouse_control.html)

[AI Virtual Mouse](https://github.com/ravigithub19/ai-virtual-mouse)



그림판 프로그램의 창 너비, 위치, 펜 색상을 변경 가능토록 하였음.

AI Virtual Mouse의 autopy는 기능 상 제한이 많아 pyautogui library를 사용하였음.

그림판 프로그램 파일을 AIVirtualMouse.py 에서 import 하여 사용하였음.



## Usage

AI Virtual Mouse로 그림을 그려보자!

1. 검지 손가락만 펼친 경우

   마우스 커서 이동

2. 검지, 엄지 손가락을 펼친 경우

   mousedown 상태. 즉, 그림을 그릴 수 있음.

3. 새끼손가락을 펼친 경우

   펜 색상이 검정색일 경우 빨간색으로, 빨간색일 경우 검정색으로 변환

4. 손가락을 모두 접은 경우

   그림 모두 지우기

5. 검지와 중지 손가락의 너비가 좁아지면 클릭



