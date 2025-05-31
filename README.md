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
