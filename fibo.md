###fibonacchi 

##index
- What is fibonacchi?
- Definition
- How to code it?(using recursive func)


##What is fibonacchi?
- 수학에서 피보나치 수는 첫째 및 둘째 항이 1이며 그 뒤의 모든 항은 바로 앞 두항의 합인 수열이다. 처음 여섯 항은 각각 1,1,2,3,5,8이다. 편의상 0번째 항을 0으로 두기도 한다.


##Definition
- F1 = F2= 1
- Fn = Fn-1 + Fn-2
0번째 항부터 시작할 경우 다음과 같이 정의된다.
- F0 = 0
- F1 = 1
- Fn = Fn-1 + Fn-2

피보나치 수의 처음 몇 항은(0번째 항부터 시작할 경우) 다음과 같다.
0,1,1,2,3,5,8,13,21,34,55,89,144,233,377,610....



##How to code it?(using recursive func)

def fib(n) :
	if n == 0;
		return 0
	elif n == 1 or n == 2:
		return 1
	else :
		return fib(n-1) + fib(n-2)


FINISH 

