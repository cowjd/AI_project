# 아두이노 드론 설계 및 PID 제어
Proportional Control (P): 현재 오차를 측정하고, 오차와 비례하는 출력을 생성합니다. 이 출력은 현재 오차에 비례하여 변화하므로, 오차가 클수록 출력이 크게 증가합니다.

Integral Control (I): 과거의 오차를 적분하여 오차의 누적 값을 계산하고, 누적 오차에 비례하는 출력을 생성합니다. 이 출력은 오랜 시간동안 일정한 오차가 유지될 경우, 점점 커지며 이 오차를 제거합니다.

Derivative Control (D): 현재 오차의 변화율에 비례하는 출력을 생성합니다. 이 출력은 현재 오차의 상승세 또는 하락세를 감지하여 제어 출력을 조절하는 데 사용됩니다.
