---
layout: singleㅣ
title: 리스트, 튜플, 셋
---


[문제 상황]
SU가 관리하는 음료수 자동판매기는 자신의 재고 변화량을 메인
컴퓨터에 업데이트 합니다. 데이터의 보호를 위해 각 자동판매기는
데이터베이스에 직접 접근하는 것이 아니라 간접적으로 접근하여
데이터를 수정하며, 이 때 각 자동판매기는 다른 자동판매기의 내
용을 변경할 수 없습니다. 메인컴퓨터의 데이터베이스와 변경된 각 자동판매기의 데이터가
다음과 같을 때 처리 과정을 적절한 자료구조를 이용하여 프로그래
밍 해 보시오.
~~~python
a=[[35,22,39,46],[12,35,98,21],[78,35,45,25]]
b=a[1]
b[1]=30
b[2]=35
print(a)
~~~

[[35, 22, 39, 46], [12, 30, 35, 21], [78, 35, 45, 25]]
