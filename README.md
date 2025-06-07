# tensorflow   

tensor차원 = axis 개수   
   
(2,2,3,4)   
1차원의 크기: 2   
2차원의 크기: 2   
3차원의 크기: 3   
4차원의 크기: 4   

**Tensorflow, Keras에서 차원**   
무조건 **batch차원**이 하나 더 붙어!!   
이미지 데이터 = (width,height,channel) 이렇게 되어있잖아   
여기서 포인트: tensorflow와 캐라스는 여기에 **배치 차원**을 붙여야함   
   결론   
   (batch,width,height,channel)   
??나는 그냥 데이터 통째로 넣을건데요??   
(1,width,height,channel)
