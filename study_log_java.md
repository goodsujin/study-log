| 2025-02-14 | static 메서드1 | public=공개여부, static=메모리 할당. / staic이어도 접근제어자로 막혀있으면 사용 불가 |
|            | static 메서드2 | static 메서드는 static만 사용 할 수 있다. '클래스 내부에서'
|            |                |(클래스 내부에서) '본인이 static이면' ⚠️static으로 된 변수나 메서드만 참조 가능⚠️|
|            |                | 1. 프로그램 시작 → static 메모리에 올라감 |
|            |                | 2. new 실행 → 그때서야 일반 변수/메서드 생김 |
|            |                | 3. static은 1번 시점에 이미 있는데, 2번이 아직 안 일어났을 수 있으니까 참조 불가 |
|            |                | but. static은 인스턴스 변수를 모르지만, 매개변수로 객체를 직접 전달하면 사용 가능 |
|            | static 메서드3 | import satatic = 정적메서드 자체를 사용할것이라고 선언 => 메소드 호출시 '클래스.메소드명' 하지 않고 바로 '메소드명 호출' 가능
|            |                | import static 패키지 위치.메소드 => 정적메소드 사용 => 바로 '메소드명()' 호출 가능.
|            |                | import static 패키지위치.클래스명.* => 바로 해당 클래스 내의 모든 메소드호출 사용가능.
|            | 연슴문제&풀이1 | <img width="584" height="657" alt="image" src="https://github.com/user-attachments/assets/27113ba7-f3ca-4489-b0b6-313dd96f9e47" />
|            | 연습문제&풀이2 |<img width="956" height="1095" alt="image" src="https://github.com/user-attachments/assets/13f20d16-00d1-4ae8-99fb-3ac33c3c06cf" />

