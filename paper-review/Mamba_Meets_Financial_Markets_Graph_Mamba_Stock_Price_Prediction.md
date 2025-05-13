
FIRST PHARAPRSING

MAMBA ?
SAMBA
RNN: input + hiddenstate_n => hiddenstate_n+1, w * hiddenstate => output
- ht_n+1 = wx*x + wh*ht_n
SSM: 연속시스템, 연속시스템을 표현하기 위해 Step(변화량)을 사용한다.
State* d/dt = (변화량)*input + (변화량)*hiddenState + C
SSM 자세히는 기억이 안나는데, 연속성을 표현하고 싶어하고 가중치, 변화량 등이 동적으로 변하는 시스템이다.
RNN은 가중치가 정해져있고, 오차역전파를 통해서 변경이 되는 시스템은 SSM은 변화량이 input의 중요도에 따라 다르게 판정된다.

SAMBDA = SSM + ?
MAMBA = SAMBA + ?



-------