# 🎫 Ticket Reserve Service

> 이벤트 티켓 예약 시스템 개발 프로젝트

## 📋 개발 규칙 가이드

### 🌿 브랜치 전략

#### 🆕 신규 기능 (feature)
```bash
feature/event-api           # 이벤트 관리 API
feature/payment-api         # 결제 처리 API
feature/user-auth          # 사용자 인증
feature/admin-dashboard    # 관리자 대시보드
```

#### 🐛 버그 수정 (fix)
```bash
fix/event-api              # 이벤트 API 버그 수정
fix/payment-api            # 결제 API 버그 수정
fix/database-connection    # DB 연결 오류 수정
fix/memory-leak           # 메모리 누수 수정
```

#### ⚡ 개선/리팩토링 (refactor)
```bash
refactor/event-manage-api         # 이벤트 관리 API 리팩토링
refactor/payment-database-queries # 결제 DB 쿼리 최적화
refactor/common-response-structure # 공통 응답 구조 개선
refactor/exception-handling       # 예외 처리 구조 개선
```

---

### 🔗 이슈 연동 키워드

| 키워드 | 동작 | 사용 예시 |
|--------|------|-----------|
| `#10` | 🔗 이슈와 연결만 (닫지 않음) | `git commit -m "feat: API 구조 설계 #10"` |
| `see #10` | 👀 이슈 참조 (닫지 않음) | `git commit -m "docs: API 문서 업데이트 see #10"` |
| `related to #10` | 📌 관련 이슈 (닫지 않음) | `git commit -m "test: 단위 테스트 추가 related to #10"` |
| `closes #10` | ✅ **이슈 닫음** | `git commit -m "feat: 이벤트 API 구현 완료 closes #10"` |
| `fixes #10` | 🔧 **이슈 닫음** | `git commit -m "fix: 좌석 중복 예약 버그 수정 fixes #10"` |

---

### 💡 커밋 메시지 컨벤션

```bash
# 형식: <type>: <description>
# 
# <body>
# 
# <footer>

feat: 이벤트 예약 API 구현

- POST /api/v1/reservations 엔드포인트 추가
- 좌석 중복 검증 로직 구현
- 예약 만료 시간 15분 설정

closes #8
```

#### 📝 커밋 타입

- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `docs`: 문서 수정
- `style`: 코드 포맷팅 (기능 변경 없음)
- `refactor`: 코드 리팩토링
- `test`: 테스트 코드 추가/수정
- `chore`: 빌드/설정 관련

---

### 🔄 워크플로우

1. **이슈 생성** → GitHub Issues에서 작업 내용 정의
2. **브랜치 생성** → `git checkout -b feature/event-api`
3. **개발 진행** → 커밋 메시지에 이슈 번호 포함
4. **Pull Request** → 코드 리뷰 요청
5. **코드 리뷰** → 팀원 검토 및 승인
6. **Merge** → `main` 브랜치로 병합 후 이슈 자동 닫힘

---

### 🛠️ 기술 스택

![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=flat-square&logo=spring)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=flat-square&logo=mysql)

---


<div align="center">

**🚀 함께 만들어가는 티켓 예약 시스템 🚀**

[![Issues](https://img.shields.io/github/issues/implement-study-25/ticket-reserve-service?style=flat-square)](https://github.com/implement-study-25/ticket-reserve-service/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/implement-study-25/ticket-reserve-service?style=flat-square)](https://github.com/implement-study-25/ticket-reserve-service/pulls)

</div>
