# 문제-(7,4)code
1. Uncoded 상황 즉, (4,4)형태로 아무런 Parity Check Bit 추가 없이 순수 데이터만 전송하는 경우
2. 주어진 (7,4)코드로 채널 코딩하여 전송하는 경우
   10000개의 패킷을 발생시켜 시뮬레이션 한 후 오류난 패킷의 확률을 구해 비교하자
# 결과
![image](https://github.com/heckzi/Mobile-Communication/assets/110593187/156b1145-7997-4c7e-87cc-8244f81c20ed)

![image](https://github.com/heckzi/Mobile-Communication/assets/110593187/909d289e-41a2-4610-8ce5-035f5b5f762d)

# 결론
7,4 코드를 이용해서 추가적인 데이터를 붙여서 보내지만 에러가 어디서 발생했는지(single
bit error 한정) Syndrome을 통해 알 수 있고 또한 에러를 수정하는 과정이 없는데도 불구하
고 그냥 메시지를 보낼 때 보다 패킷 오류 확률이 적은 것을 확인 할 수 있었다.
