# Developermode.github.io

🌟 **개인 포트폴리오 웹사이트** 🌟

현대적이고 반응형인 개인 포트폴리오 웹사이트입니다. HTML, CSS, JavaScript를 사용하여 제작되었으며, GitHub Pages를 통해 호스팅됩니다.

## ✨ 주요 기능

- 🎨 **모던한 디자인**: 그라디언트와 애니메이션을 활용한 아름다운 UI
- 📱 **완전 반응형**: 모든 디바이스에서 완벽하게 작동
- 🚀 **부드러운 애니메이션**: 스크롤 기반 애니메이션과 상호작용 효과
- 📧 **연락처 폼**: 방문자가 직접 메시지를 보낼 수 있는 기능
- 🔍 **SEO 최적화**: 검색 엔진 최적화된 구조

## 🛠 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **JavaScript**: ES6+, DOM 조작, Intersection Observer
- **Font Awesome**: 아이콘
- **Google Fonts**: 웹 폰트

## 📁 프로젝트 구조

```
Developermode.github.io/
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 기능
└── README.md           # 프로젝트 문서
```

## 🚀 로컬 개발

1. **저장소 클론**
   ```bash
   git clone https://github.com/yourusername/Developermode.github.io.git
   cd Developermode.github.io
   ```

2. **로컬 서버 실행**
   - Live Server 확장을 사용하거나
   - Python 서버: `python -m http.server 8000`
   - Node.js 서버: `npx serve .`

3. **브라우저에서 확인**
   ```
   http://localhost:8000
   ```

## 📝 커스터마이징

### 개인 정보 수정
1. `index.html`에서 다음 섹션들을 수정하세요:
   - 이름과 소개
   - 프로젝트 정보
   - 연락처 정보

### 스타일 변경
1. `styles.css`의 `:root` 섹션에서 색상 변수 수정:
   ```css
   :root {
       --primary-color: #667eea;
       --secondary-color: #764ba2;
       --accent-color: #f093fb;
   }
   ```

### 프로젝트 추가
1. `index.html`의 프로젝트 섹션에서 새로운 `project-card` 추가

## 🌐 배포

GitHub Pages를 통한 자동 배포:

1. **설정 확인**
   - GitHub 저장소가 `username.github.io` 형태인지 확인
   - 또는 다른 저장소명의 경우 Settings > Pages에서 설정

2. **자동 배포**
   - `main` 브랜치에 푸시하면 자동으로 배포됩니다
   - 배포 URL: `https://yourusername.github.io`

## 📱 섹션 소개

- **Hero**: 첫인상을 담당하는 메인 섹션
- **About**: 개인 소개와 통계
- **Skills**: 기술 스택 소개
- **Projects**: 포트폴리오 프로젝트들
- **Contact**: 연락처 정보 및 메시지 폼

## 🎯 향후 개선 사항

- [ ] 다크 모드 지원
- [ ] 다국어 지원
- [ ] 블로그 섹션 추가
- [ ] 프로젝트 필터링 기능
- [ ] 백엔드 연동으로 실제 메일 발송

## 📄 라이선스

MIT License - 자유롭게 사용, 수정, 배포할 수 있습니다.

## 🤝 기여

풀 리퀘스트와 이슈는 언제나 환영합니다!

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요!