# TechStack-Study

Java와 Spring을 중심으로 배운 개념, 프로젝트 실습, 배포 중 겪은 문제와 해결 과정을 날짜별로 기록합니다.

전체 학습 기록은 [DailyLog](docs/DailyLog/)에서 날짜별로 볼 수 있습니다.

## 학습 주제와 대표 기록

| 주제 | 공부한 내용 | 대표 기록 |
| --- | --- | --- |
| Java 기초 | 클래스와 객체, 인터페이스, 예외 처리, 컬렉션 | [클래스와 객체](docs/DailyLog/2026-08-03.md) · [컬렉션](docs/DailyLog/2026-08-07.md) |
| Java 웹 개발 | JSP·Servlet의 요청과 응답, MVC, DAO·JDBC를 통한 DB 연동 | [회원 등록과 조회 흐름](docs/DailyLog/2026-08-20.md) · [MVC 실습](docs/DailyLog/2026-08-27.md) |
| 브라우저 통신과 디버깅 | JSON·AJAX·WebSocket, Chrome 개발자 도구에서 실행 흐름과 변수 확인 | [JSON·AJAX·WebSocket](docs/DailyLog/2026-09-08.md) · [브레이크포인트 실습](docs/DailyLog/2026-11-19.md) |
| Spring Boot와 데이터베이스 | REST API 설계, JPA와 영속성 컨텍스트 | [REST API와 JPA](docs/DailyLog/2026-10-27.md) |
| 인증과 인가 | Spring Security, JWT, Google OAuth2 로그인 | [JWT 인증 흐름](docs/DailyLog/2026-11-02.md) · [Google 로그인 흐름](docs/DailyLog/2026-11-03.md) |
| 배포와 운영 | AWS EC2와 MySQL, GitHub Actions 배포, Nginx와 HTTPS 적용 | [EC2 배포 구성](docs/DailyLog/2026-11-11.md) · [StoreCRM 배포 트러블슈팅](docs/DailyLog/2026-11-25.md) |

## DailyLog 기록 방식

- **개념 복습**은 배운 내용을 내 말로 정리하고, 코드 예시나 요청 흐름을 따라가며 이해한 내용을 확인합니다.
- **프로젝트 실습**은 그날의 목표, 진행한 작업, 직접 확인한 결과와 다음에 복습할 내용을 남깁니다.
- **트러블슈팅**은 증상, 로그나 설정에서 확인한 단서, 원인과 해결 과정을 기록합니다. [StoreCRM 배포 기록](docs/DailyLog/2026-11-25.md)에는 HTTPS 적용 중 발생한 Google 로그인 오류와 서비스 재시작 후 발생한 `502 Bad Gateway`를 해결한 과정이 담겨 있습니다.
