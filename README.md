### 커밋 타입

- `feat`: 새로운 기능
- `fix`: 버그 수정
- `docs`: 문서 수정
- `style`: 코드 포맷팅
- `refactor`: 리팩토링
- `test`: 테스트 추가
- `chore`: 빌드, 의존성 등

### PR 규칙

- PR 제목: `feat: 공통 UI 컴포넌트 구현 (closes #1)`

### 코드 스타일

- ESLint + Prettier 자동 적용
- 커밋 전 자동 lint-staged 실행
- 푸시 전 자동 빌드 체크

### 배포

- `develop` 브랜치 → 자동 프로덕션 배포
- `main` 브랜치 → 프로덕션 배포
- PR → 미리보기 배포

---

## 🛠️ 개발 환경 설정

### 필수 도구

- Node.js 20.x
- npm
- Git

### 설치 및 실행

```bash
npm install
npm run dev
```

### 스크립트

- `npm run dev`: 개발 서버
- `npm run build`: 빌드
- `npm run lint`: 린트 체크
- `npm run format`: 포맷팅

---

## 📋 이슈 템플릿

- Feature Request
- Bug Report
- Chore Task

## 🔗 링크

- [배포 URL](https://taja-project.vercel.app)
