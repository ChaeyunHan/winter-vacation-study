## **퍼셉트론**

퍼셉트론은 프랑크 로젠블라트가 처음 고안한 알고리즘입니다.

이는 신경망과 딥러닝으로 나아가는 데 중요한 역할을 합니다.

[##_Image|kage@wWTWM/btqAWxa3Ido/3uuRJXQpuSfTZGUDKxUaK0/img.png|alignLeft|data-filename="0_LJBO8UbtzK_SKMog.png" data-origin-width="645" data-origin-height="351" width="536" height="292"|Perceptron||_##]

퍼셉트론은 "다수 입력 - 단일 출력"의 형태입니다.

여러개의 신호가 입력되면 하나의 신호가 출력됩니다.  

입력값(x)에 가중치(w)를 곱하여 모두 합하면 출력값이 됩니다.

**x1\*w1+x2\*w2+x3\*w3 +b <=0 이면 y=0**

**x1\*w1+x2\*w2+x3\*w3 +b >0 이면 y=1**

**b(bias)**는 편향을 나타내는 매개변수이고 활성화를 제어합니다.  

**w(weight)**는 가중치를 나타내고 각 입력값의 영향력을 제어합니다.

## **인공신경망**

[##_Image|kage@bzSELp/btqATg2Kag5/4sVKksrsLgC8YWYRGNgWyK/img.jpg|alignLeft|data-filename="n.JPG" data-origin-width="630" data-origin-height="567" width="451" height="406"|neural network||_##]

-   동그라미 = 노드
    
-   회색 선 = 가중치
    

인공신경망은 다음과 같이 **입력층(input layer)**, **은닉층(hidden layer)**, **출력층(output layer)**으로 되어있습니다.

위 그림에서는 2개의 입력과 2개 출력이 있습니다. 

1\. 입력층은 출력변수를 잘 도출하기 위해 입력변수 값을 입력합니다.

2\. 은닉층에서는 입력값을 받아 가중합을 계산하고 출력층에 전달하게 됩니다.

3\. 이 가중치는 초기에는 랜덤으로 주어지고 점점 예측을 잘 하도록 조정됩니다.