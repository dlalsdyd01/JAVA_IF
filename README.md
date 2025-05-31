# JAVA_IF  

## ✅ if란? 조건에 따라 실행할 코드를 선택할 수 있게 해주는 조건문.  
  
```
int age = 20;

if (age >= 18) {
    System.out.println("성인입니다.");
}
```

논리 연산자 And 사용  
```
int age = 25;
boolean hasTicket = true;

if (age >= 18 && hasTicket) {
    System.out.println("입장 가능합니다.");
```

논리 연산자 Or 사용
```
int age = 70;
boolean isPregnant = false;

if (age >= 65 || isPregnant) {
    System.out.println("우선 탑승 대상입니다.");
```

if의 {} 중괄호는 한 줄만 실행할 때 생략 가능하다  



# if ~ else  
```
if (조건) {
    // 조건이 참(true)일 때 실행
} else {
    // 조건이 거짓(false)일 때 실행
}
```
  
```
int age = 16;

if (age >= 18) {
    System.out.println("성인입니다.");
} else {
    System.out.println("미성년자입니다.");
}
```


# else if  
```
if (조건1) {
    // 조건1이 참일 때 실행
} else if (조건2) {
    // 조건2가 참일 때 실행
} else {
    // 모든 조건이 거짓일 때 실행
}
```
예제  
```
int score = 85;

if (score >= 90) {
    System.out.println("A등급");
} else if (score >= 80) {
    System.out.println("B등급");
} else if (score >= 70) {
    System.out.println("C등급");
} else {
    System.out.println("F등급");
}
```

# Switch Case  

```
switch (변수) {
    case 값1:
        // 변수 == 값1 일 때 실행 코드
        break;
    case 값2:
        // 변수 == 값2 일 때 실행 코드
        break;
    ...
    default:
        // 모든 case에 해당하지 않을 때 실행
}
```
예제  
```
int num = 2;

switch (num) {
    case 1:
        System.out.println("하나");
        break;
    case 2:
        System.out.println("둘");
        break;
    default:
        System.out.println("그 외 숫자");
}
```

break는 해당 case 실행 후 switch문을 종료하고 빠져나가게 한다.  
break가 없으면 그 다음 case들도 계속해서 실행된다.
