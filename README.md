# Deep-learning-from-scratch-3

『밑바닥부터 시작하는 딥러닝 ❸』에서는 'DeZero'라는 이 책의 오리지널 딥러닝 프레임워크를 만듭니다. DeZero는 파이토치와 텐서플로 2.0 같은 현대적인 프레임워크가 채택한 동적 계산 그래프(Define-by-Run) 방식의 프레임워크입니다. 최소한의 코드로, 하지만 충분히 강력한 프레임워크를 총 5개 고지, 60단계에 걸쳐 점진적으로 완성합니다. 마지막 고지에서는 직접 만든 프레임워크 위에서 VGG16과 LSTM 같은 신경망을 돌려보기도 합니다. 이 과정에서 여러분은 다음과 같은 효과를 얻으실 수 있을 겁니다.
 
* 파이토치, 텐서플로 2.0 같은 현대적인 딥러닝 프레임워크의 동작 원리를 깨우친다.
* 현대적인 딥러닝 프레임워크를 떠받드는 기술과 사상을 들여다본다.
* 딥러닝을 한 차원 깊게 이해한다.
* ‘프레임워크’를 직접 개발해보는 경험을 쌓아, 개발자로서 한 단계 성장한다.
* 유용한 파이썬 프로그래밍 관례를 익힌다.
* 파이토치, 텐서플로 2, 체이너 같은 현대적 프레임워크의 소스 코드를 더욱 쉽게 분석하고 이해할 수 있다.


<a href="https://github.com/WegraLee/deep-learning-from-scratch-3/blob/master/DeZeroClasses.pdf"><img src="https://github.com/WegraLee/deep-learning-from-scratch-3/blob/master/DeZeroClasses.png" width=1000></a>

## 파일 구성

|폴더 이름 |설명                         |
|:--        |:--                          |
|[dezero](/dezero)       |DeZero의 소스 코드 |
|[examples](/examples)      |Dezero를 사용한 구현 예    |
|[steps](/steps)|각 단계의 파일（step01.py ~ step60.py）|
|[tests](/tests)|DeZero 단위 테스트|

## 요구사항
소스 코드를 실행하려면 아래의 소프트웨어가 설치되어 있어야 합니다.

- [Python 3.3 이상](https://docs.python.org/3/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

또한 선택사항으로 엔비디아 GPU에서 수행할 수 있는 기능도 제공합니다. 이 경우 다음 라이브러리가 필요합니다.

- [CuPy](https://cupy.chainer.org/) （선택사항）
