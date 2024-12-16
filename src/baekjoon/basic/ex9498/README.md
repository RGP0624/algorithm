## IF조건문

```
if ( a >= 90 ) {
System.out.println("A");
} else if (a >= 80) {
System.out.println("B");
} else if (a >= 70) {
System.out.println("C");
} else if (a >= 60) {
System.out.println("D");
} else {
System.out.println("F");
}
```
- if (조건) { 실행문 } -> 조건이 true 면 실행 false면 실행 안됨 
- else if (조건) { 실행문 } -> if문 다음 else if (if문 조건 false일 때 조건 확인) 
- else { 실행문 } -> 전 조건문 false 일 떄 실행