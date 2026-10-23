# Formwheel_AI

기억을 사용하고 대화를 통해 발전하도록 만든 FormWheel AI 실험.

- 실행: https://semicolonxss.github.io/Formwheel_AI/
- 프로젝트 목록: https://semicolonxss.github.io/Formwheel/
- 진행 상태: https://semicolonxss.github.io/Formwheel_Check/

## 사용

브라우저에서 실행 링크를 여세요. 화면에 표시된 설명과 버튼으로 진행합니다. 온라인 기능은 Firebase 연결이 필요하며, 방 게임은 같은 코드로 참가합니다. 로컬 저장은 현재 브라우저에만 남습니다.

## 개발 및 검증

정적 HTML/JavaScript 프로젝트입니다. HTTP 서버로 제공하세요. Firebase 운영 설정·Rules는 이 저장소의 화면 파일만 배포해서 바뀌지 않습니다.

```sh
node scripts/check-syntax.cjs
```

첫 검사는 JavaScript 구문과 상대경로 파일 존재를 확인합니다. 모든 앱의 실제 멀티플레이와 운영 권한을 보증하는 검사는 아닙니다.

## 데이터 및 운영 보안

공통 안내: https://semicolonxss.github.io/Formwheel/privacy.html

닉네임·답안·점수·채팅 등이 서버에 저장될 수 있습니다. 새 보안 스키마와 서버 코드는 [Formwheel/firebase-security](https://github.com/SemicolonXSS/Formwheel/tree/main/firebase-security)에 준비했습니다. 현재 운영 적용 및 기존 경로 전환이 완료되었다고 가정하지 마세요. 계정/제공자 설정, 서버 보안 검증이 필요한 항목은 Check에서 별도로 남겨둡니다.

화면 마크업은 `index.html`, 앱별 스타일과 실행 코드는 `assets/`에 분리했습니다. 공통 UI는 Formwheel 저장소의 `shared/`를 사용합니다.

## 🎮 게임 가이드

**성장형 AI 프로젝트** — 대화와 반응을 통해 변화하는 Formwheel AI 프로젝트입니다.

### 플레이 방법

1. AI 화면 실행
2. 입력창에 메시지 작성
3. 답변과 성장 상태 확인

### 주요 기능

- 대화
- 성장 단계
- 상호작용

> 구체적인 지원 모드와 버튼 이름은 배포 버전에 따라 달라질 수 있습니다.

<!-- FORMWHEEL-README-2026 -->
## 🎡 Formwheel 프로젝트 안내

**Formwheel AI** — AI 실험 프로젝트.

- [프로젝트 열기](https://semicolonxss.github.io/Formwheel_AI/) · [Hub](https://semicolonxss.github.io/Formwheel/)
- [개발 현황](https://semicolonxss.github.io/Formwheel_Check/) · [피드백](https://semicolonxss.github.io/Formwheel/feedback.html)

프로젝트별 기능과 로그인·동기화 지원 범위는 다를 수 있습니다. 오류를 제보할 때는 재현 단계와 기기·브라우저 정보를 남겨 주세요. 비밀번호와 인증 토큰은 공유하지 마세요.
