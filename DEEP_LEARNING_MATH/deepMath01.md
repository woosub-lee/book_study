# 딥러닝을 위한 수학  
## 미분과 적분
### 함수
#### 함수란?
하나의 입력값을 넣었을때 오로지 하나의 출력 값만 나오게 하는 것  
**프로그래밍에서의 function이 아니라 수학적 함수입니다.**  
#### 합성함수와 역함수
* 합성함수  
![Large](https://latex.codecogs.com/gif.latex?f%28x%29%3Dx%5E2&plus;1)  
![Large](https://latex.codecogs.com/gif.latex?g%28x%29%3D%5Csqrt%7Bx%7D)  
![Large](https://latex.codecogs.com/gif.latex?%5Csqrt%7Bx%5E2&plus;1%7D%3Dg%5Ccirc%7Bf%28x%29%7D)  
위와 같이 나타낼 수 있다.  
단순한 함수의 결합으로 복잡한 미분 계산을 쉽게 할 수 있다.  
이러한 미분법을 **연쇄 법칙**이라 한다.
* 역함수  
입력이 f(x)의 출력, 출력의 f(x)의 입력인 함수다.  
역함수가 존재하려면 x값이 다를 때 y값이 같은 경우가 없어야 한다. **일대일 대응**  
역함수가 존재하게 만들기 위해서는 정의역을 제한해야 한다.
### 미분
#### 미분의 정의
**함수의 그래프 위에 있는 한 점을 중심으로 확대하다보면 그래프의 모양이 직선에 가까워지는데, 이때의 기울기를 미분이라 한다.**  
극한 개념 추가 요망  
![Large](https://latex.codecogs.com/gif.latex?%5Clim_%7Bh%20%5Cto%20%5C0%7D%5Cfrac%7Bf%28x&plus;h%29-f%28x%29%7D%7Bh%7D)  
h가 한없이 0에 가까워 질때의 식이 함수 f(x)의 미분이다.
