# 📒 Effective Java 3/E

## 2장 객체 생성과 파괴

| 아이템 이름 | 주제 |
|--------|--------|
| Item 1 | [생성자 대신 정적 팩터리 메서드를 고려하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem1%5D%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%84%B0%EB%A6%AC%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md) |
| Item 2 | [생성자에 매개변수가 많다면 빌더를 고려하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem2%5D%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md) |
| Item 3 | [private 생성자나 열거 타입으로 싱글턴임을 보증하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem3%5Dprivate%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C%20%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84%20%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC.md) |
| Item 4 | [인스턴스화를 막으려거든 private 생성자를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem4%5D%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EC%9C%BC%EB%A0%A4%EA%B1%B0%EB%93%A0%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 5 | [자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem5%5D%EC%9E%90%EC%9B%90%EC%9D%84%20%EC%A7%81%EC%A0%91%20%EB%AA%85%EC%8B%9C%ED%95%98%EC%A7%80%20%EB%A7%90%EA%B3%A0%20%EC%9D%98%EC%A1%B4%20%EA%B0%9D%EC%B2%B4%20%EC%A3%BC%EC%9E%85%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 6 | [불필요한 객체 생성을 피하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem6%5D%EB%B6%88%ED%95%84%EC%9A%94%ED%95%9C%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EC%9D%84%20%ED%94%BC%ED%95%98%EB%9D%BC.md) |
| Item 7 | [다 쓴 객체 참조를 해제하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem7%5D%EB%8B%A4%20%EC%93%B4%20%EA%B0%9D%EC%B2%B4%20%EC%B0%B8%EC%A1%B0%EB%A5%BC%20%ED%95%B4%EC%A0%9C%ED%95%98%EB%9D%BC.md) |
| Item 8 | [finalizer와 cleaner 사용을 피하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem8%5Dfinalizer%EC%99%80%20cleaner%20%EC%82%AC%EC%9A%A9%EC%9D%84%20%ED%94%BC%ED%95%98%EB%9D%BC.md) |
| Item 9 | [try-finally보다는 try-with-resources를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/2%EC%9E%A5%20%EA%B0%9D%EC%B2%B4%20%EC%83%9D%EC%84%B1%EA%B3%BC%20%ED%8C%8C%EA%B4%B4%20(Object%20creation%20and%20destruction)/%5Bitem9%5Dtry-finally%EB%B3%B4%EB%8B%A4%EB%8A%94%20try-with-resources%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |

## 3장 모든 객체의 공통 메서드

| 아이템 이름 | 주제 |
|--------|--------|
| Item 10 | [equals는 일반 규약을 지켜 재정의하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/3%EC%9E%A5/%5Bitem10%5Dequals%EB%8A%94%20%EC%9D%BC%EB%B0%98%20%EA%B7%9C%EC%95%BD%EC%9D%84%20%EC%A7%80%EC%BC%9C%20%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.md) |

## 4장 클래스와 인터페이스

| 아이템 이름 | 주제 |
|--------|--------|
| Item 15 | [클래스와 멤버의 접근 권한을 최소화하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5/%5Bitem15%5D%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80%20%EB%A9%A4%EB%B2%84%EC%9D%98%20%EC%A0%91%EA%B7%BC%20%EA%B6%8C%ED%95%9C%EC%9D%84%20%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.md) |
| Item 16 | [public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5/%5Bitem16%5Dpublic%20%ED%81%B4%EB%9E%98%EC%8A%A4%EC%97%90%EC%84%9C%EB%8A%94%20public%20%ED%95%84%EB%93%9C%EA%B0%80%20%EC%95%84%EB%8B%8C%20%EC%A0%91%EA%B7%BC%EC%9E%90%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 17 | [변경 가능성을 최소화하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5/%5Bitem17%5D%EB%B3%80%EA%B2%BD%20%EA%B0%80%EB%8A%A5%EC%84%B1%EC%9D%84%20%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.md) |
| Item 18 | [상속보다는 컴포지션을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5/%5Bitem18%5D%EC%83%81%EC%86%8D%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EC%BB%B4%ED%8F%AC%EC%A7%80%EC%85%98%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 19 | [상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5%20%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4(Classes%20and%20Interfaces)/%5Bitem19%5D%EC%83%81%EC%86%8D%EC%9D%84%20%EA%B3%A0%EB%A0%A4%ED%95%B4%20%EC%84%A4%EA%B3%84%ED%95%98%EA%B3%A0%20%EB%AC%B8%EC%84%9C%ED%99%94%ED%95%98%EB%9D%BC.%20%EA%B7%B8%EB%9F%AC%EC%A7%80%20%EC%95%8A%EC%95%98%EB%8B%A4%EB%A9%B4%20%EC%83%81%EC%86%8D%EC%9D%84%20%EA%B8%88%EC%A7%80%ED%95%98%EB%9D%BC.md) |
| Item 20 | [추상 클래스보다는 인터페이스를 우선하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/4%EC%9E%A5%20%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4(Classes%20and%20Interfaces)/%5Bitem20%5D%EC%B6%94%EC%83%81%20%ED%81%B4%EB%9E%98%EC%8A%A4%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC%20%EC%9A%B0%EC%84%A0%ED%95%98%EB%9D%BC.md) |

## 5장 제네릭

| 아이템 이름 | 주제 |
|--------|--------|
| Item 26 | [로 타입을 사용하지 마라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem26%5D%EB%A1%9C%20%ED%83%80%EC%9E%85%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%A7%80%20%EB%A7%88%EB%9D%BC.md) |
| Item 27 | [비검사 경고를 제거하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem27%5D%EB%B9%84%EA%B2%80%EC%82%AC%20%EA%B2%BD%EA%B3%A0%EB%A5%BC%20%EC%A0%9C%EA%B1%B0%ED%95%98%EB%9D%BC.md) |
| Item 28 | [배열보다는 리스트를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem28%5D%EB%B0%B0%EC%97%B4%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EB%A6%AC%EC%8A%A4%ED%8A%B8%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 29 | [이왕이면 제네릭 타입으로 만들라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem29%5D%EC%9D%B4%EC%99%95%EC%9D%B4%EB%A9%B4%20%EC%A0%9C%EB%84%A4%EB%A6%AD%20%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C%20%EB%A7%8C%EB%93%A4%EB%9D%BC.md) |
| Item 30 | [이왕이면 제네릭 메서드로 만들라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem30%5D%EC%9D%B4%EC%99%95%EC%9D%B4%EB%A9%B4%20%EC%A0%9C%EB%84%A4%EB%A6%AD%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%A1%9C%20%EB%A7%8C%EB%93%A4%EB%9D%BC.md) |
| Item 31 | [한정적 와일드카드를 사용해 API 유연성을 높이라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem31%5D%ED%95%9C%EC%A0%95%EC%A0%81%20%EC%99%80%EC%9D%BC%EB%93%9C%EC%B9%B4%EB%93%9C%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%B4%20API%20%EC%9C%A0%EC%97%B0%EC%84%B1%EC%9D%84%20%EB%86%92%EC%9D%B4%EB%9D%BC.md) |
| Item 32 | [제네릭과 가변인수를 함께 쓸 때는 신중하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem32%5D%EC%A0%9C%EB%84%A4%EB%A6%AD%EA%B3%BC%20%EA%B0%80%EB%B3%80%EC%9D%B8%EC%88%98%EB%A5%BC%20%ED%95%A8%EA%BB%98%20%EC%93%B8%20%EB%95%8C%EB%8A%94%20%EC%8B%A0%EC%A4%91%ED%95%98%EB%9D%BC.md) |
| Item 33 | [타입 안전 이종 컨테이너를 고려하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/5%EC%9E%A5%20%EC%A0%9C%EB%84%A4%EB%A6%AD(Generic)/%5Bitem33%5D%ED%83%80%EC%9E%85%20%EC%95%88%EC%A0%84%20%EC%9D%B4%EC%A2%85%20%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md) |

## 6장 열거 타입과 애너테이션

| 아이템 이름 | 주제 |
|--------|--------|
| Item 34 | [int 상수 대신 열거 타입을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/6%EC%9E%A5%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EA%B3%BC%20%EC%95%A0%EB%84%88%ED%85%8C%EC%9D%B4%EC%85%98%20(Enum%20type%20and%20annotation)/%5Bitem34%5Dint%20%EC%83%81%EC%88%98%20%EB%8C%80%EC%8B%A0%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 35 | [ordinal 메서드 대신 인스턴스 필드를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/6%EC%9E%A5%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EA%B3%BC%20%EC%95%A0%EB%84%88%ED%85%8C%EC%9D%B4%EC%85%98%20(Enum%20type%20and%20annotation)/%5Bitem35%5Dordinal%20%EB%A9%94%EC%84%9C%EB%93%9C%20%EB%8C%80%EC%8B%A0%20%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%20%ED%95%84%EB%93%9C%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 36 | [비트 필드 대신 EnumSet을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/6%EC%9E%A5%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EA%B3%BC%20%EC%95%A0%EB%84%88%ED%85%8C%EC%9D%B4%EC%85%98%20(Enum%20type%20and%20annotation)/%5Bitem36%5D%EB%B9%84%ED%8A%B8%20%ED%95%84%EB%93%9C%20%EB%8C%80%EC%8B%A0%20EnumSet%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |

## 7장 람다와 스트림

| 아이템 이름 | 주제 |
|--------|--------|

## 8장 메서드

| 아이템 이름 | 주제 |
|--------|--------|

## 9장 일반적인 프로그래밍 원칙

| 아이템 이름 | 주제 |
|--------|--------|
| Item 57 | [지역변수의 범위를 최소화하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem57%5D%EC%A7%80%EC%97%AD%EB%B3%80%EC%88%98%EC%9D%98%20%EB%B2%94%EC%9C%84%EB%A5%BC%20%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.md) |
| Item 58 | [전통적인 for 문보다는 for-each문을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem58%5D%EC%A0%84%ED%86%B5%EC%A0%81%EC%9D%B8%20for%20%EB%AC%B8%EB%B3%B4%EB%8B%A4%EB%8A%94%20for-each%EB%AC%B8%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 59 | [라이브러리를 익히고 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem59%5D%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC%EB%A5%BC%20%EC%9D%B5%ED%9E%88%EA%B3%A0%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 60 | [정확한 답이 필요하다면 float와 double은 피하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem60%5D%EC%A0%95%ED%99%95%ED%95%9C%20%EB%8B%B5%EC%9D%B4%20%ED%95%84%EC%9A%94%ED%95%98%EB%8B%A4%EB%A9%B4%20float%EC%99%80%20double%EC%9D%80%20%ED%94%BC%ED%95%98%EB%9D%BC.md) |
| Item 61 | [박싱된 기본 타입보다는 기본 타입을 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem61%5D%EB%B0%95%EC%8B%B1%EB%90%9C%20%EA%B8%B0%EB%B3%B8%20%ED%83%80%EC%9E%85%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EA%B8%B0%EB%B3%B8%20%ED%83%80%EC%9E%85%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 62 | [다른 타입이 적절하다면 문자열 사용을 피하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem62%5D%EB%8B%A4%EB%A5%B8%20%ED%83%80%EC%9E%85%EC%9D%B4%20%EC%A0%81%EC%A0%88%ED%95%98%EB%8B%A4%EB%A9%B4%20%EB%AC%B8%EC%9E%90%EC%97%B4%20%EC%82%AC%EC%9A%A9%EC%9D%84%20%ED%94%BC%ED%95%98%EB%9D%BC.md) |
| Item 63 | [문자열 연결은 느리니 주의하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem63%5D%EB%AC%B8%EC%9E%90%EC%97%B4%20%EC%97%B0%EA%B2%B0%EC%9D%80%20%EB%8A%90%EB%A6%AC%EB%8B%88%20%EC%A3%BC%EC%9D%98%ED%95%98%EB%9D%BC.md) |
| Item 64 | [객체는 인터페이스를 사용해 참조하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem64%5D%EA%B0%9D%EC%B2%B4%EB%8A%94%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%B4%20%EC%B0%B8%EC%A1%B0%ED%95%98%EB%9D%BC.md) |
| Item 65 | [리플렉션보다는 인터페이스를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem65%5D%EB%A6%AC%ED%94%8C%EB%A0%89%EC%85%98%EB%B3%B4%EB%8B%A4%EB%8A%94%20%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 66 | [네이티브 메서드는 신중히 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem66%5D%EB%84%A4%EC%9D%B4%ED%8B%B0%EB%B8%8C%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%8A%94%20%EC%8B%A0%EC%A4%91%ED%9E%88%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 67 | [최적화는 신중히 하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem67%5D%EC%B5%9C%EC%A0%81%ED%99%94%EB%8A%94%20%EC%8B%A0%EC%A4%91%ED%9E%88%20%ED%95%98%EB%9D%BC%1D.md) |
| Item 68 | [일반적으로 통용되는 명명 규칙을 따르라](https://github.com/NoSubject-Study/effective-java-study/blob/main/9%EC%9E%A5%20%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%9B%90%EC%B9%99%20(General%20Programming%20Principle)/%5Bitem68%5D%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9C%BC%EB%A1%9C%20%ED%86%B5%EC%9A%A9%EB%90%98%EB%8A%94%20%EB%AA%85%EB%AA%85%20%EA%B7%9C%EC%B9%99%EC%9D%84%20%EB%94%B0%EB%A5%B4%EB%9D%BC.md) |

## 10장 예외

| 아이템 이름 | 주제 |
|--------|--------|
| Item 69 | [예외는 진짜 예외 상황에만 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2069.%20%EC%98%88%EC%99%B8%EB%8A%94%20%EC%A7%84%EC%A7%9C%20%EC%98%88%EC%99%B8%20%EC%83%81%ED%99%A9%EC%97%90%EB%A7%8C%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 70 | [복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2070.%20%EB%B3%B5%EA%B5%AC%ED%95%A0%20%EC%88%98%20%EC%9E%88%EB%8A%94%20%EC%83%81%ED%99%A9%EC%97%90%EB%8A%94%20%EA%B2%80%EC%82%AC%20%EC%98%88%EC%99%B8%EB%A5%BC%2C%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%98%A4%EB%A5%98%EC%97%90%EB%8A%94%20%EB%9F%B0%ED%83%80%EC%9E%84%20%EC%98%88%EC%99%B8%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) |
| Item 71 | [필요 없는 검사 예외 사용은 피하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2071.%20%ED%95%84%EC%9A%94%20%EC%97%86%EB%8A%94%20%EA%B2%80%EC%82%AC%20%EC%98%88%EC%99%B8%20%EC%82%AC%EC%9A%A9%EC%9D%80%20%ED%94%BC%ED%95%98%EB%9D%BC.md) |
| Item 72 | [표준예외를 사용해라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2072.%20%ED%91%9C%EC%A4%80%EC%98%88%EC%99%B8%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%B4%EB%9D%BC.md) |
| Item 73 | [추상화 수준에 맞는 예외를 던져라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2073.%20%EC%B6%94%EC%83%81%ED%99%94%20%EC%88%98%EC%A4%80%EC%97%90%20%EB%A7%9E%EB%8A%94%20%EC%98%88%EC%99%B8%EB%A5%BC%20%EB%8D%98%EC%A0%B8%EB%9D%BC.md) |
| Item 74 | [메서드가 던지는 모든 예외를 문서화하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2074.%20%EB%A9%94%EC%84%9C%EB%93%9C%EA%B0%80%20%EB%8D%98%EC%A7%80%EB%8A%94%20%EB%AA%A8%EB%93%A0%20%EC%98%88%EC%99%B8%EB%A5%BC%20%EB%AC%B8%EC%84%9C%ED%99%94%ED%95%98%EB%9D%BC.md) |
| Item 75 | [예외의 상세 메시지에 실패 관련 정보를 담으라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2075.%20%EC%98%88%EC%99%B8%EC%9D%98%20%EC%83%81%EC%84%B8%20%EB%A9%94%EC%8B%9C%EC%A7%80%EC%97%90%20%EC%8B%A4%ED%8C%A8%20%EA%B4%80%EB%A0%A8%20%EC%A0%95%EB%B3%B4%EB%A5%BC%20%EB%8B%B4%EC%9C%BC%EB%9D%BC.md) |
| Item 76 | [가능한 한 실패 원자적으로 만들라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2076.%20%EA%B0%80%EB%8A%A5%ED%95%9C%20%ED%95%9C%20%EC%8B%A4%ED%8C%A8%20%EC%9B%90%EC%9E%90%EC%A0%81%EC%9C%BC%EB%A1%9C%20%EB%A7%8C%EB%93%A4%EB%9D%BC.md) |
| Item 77 | [예외를 무시하지 말라](https://github.com/NoSubject-Study/effective-java-study/blob/main/10%EC%9E%A5%20%EC%98%88%EC%99%B8(Exceptions)/item%2077.%20%EC%98%88%EC%99%B8%EB%A5%BC%20%EB%AC%B4%EC%8B%9C%ED%95%98%EC%A7%80%20%EB%A7%90%EB%9D%BC.md) |

## 11장 동시성

| 아이템 이름 | 주제 |
|--------|--------|

## 12장 직렬화

| 아이템 이름 | 주제 |
|--------|--------|
| Item 85 | [자바 직렬화의 대안을 찾으라](https://github.com/NoSubject-Study/effective-java-study/blob/main/12%EC%9E%A5%20%EC%A7%81%EB%A0%AC%ED%99%94(Serialize)/%5Bitem85%5D%EC%9E%90%EB%B0%94%20%EC%A7%81%EB%A0%AC%ED%99%94%EC%9D%98%20%EB%8C%80%EC%95%88%EC%9D%84%20%EC%B0%BE%EC%9C%BC%EB%9D%BC.md) |
| Item 86 | [Serializable을 구현할지는 신중히 결정하라](https://github.com/NoSubject-Study/effective-java-study/blob/main/12%EC%9E%A5%20%EC%A7%81%EB%A0%AC%ED%99%94(Serialize)/%5Bitem86%5DSerializable%EC%9D%84%20%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80%EB%8A%94%20%EC%8B%A0%EC%A4%91%ED%9E%88%20%EA%B2%B0%EC%A0%95%ED%95%98%EB%9D%BC.md) |
| Item 87 | [커스텀 직렬화 형태를 고려해보라](https://github.com/NoSubject-Study/effective-java-study/blob/main/12%EC%9E%A5%20%EC%A7%81%EB%A0%AC%ED%99%94(Serialize)/%5Bitem87%5D%EC%BB%A4%EC%8A%A4%ED%85%80%20%EC%A7%81%EB%A0%AC%ED%99%94%20%ED%98%95%ED%83%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%B4%EB%B3%B4%EB%9D%BC.md) |

