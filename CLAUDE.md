# CLAUDE.md

이 파일은 Claude Code (claude.ai/code)가 이 저장소의 코드를 다룰 때 참고하는 가이드입니다.

## 프로젝트 개요

**4hours Soft** - 모바일 앱 개발 회사 웹사이트

- **도메인**: 4hourssoft.com
- **호스팅**: GitHub Pages (정적 웹사이트)

## 프로젝트 구조

```
/
├── index.html          # 메인 랜딩 페이지
├── privacy.html        # 기본 개인정보처리방침
├── privacy*.html       # 앱별 개인정보처리방침 (001, 005, 013, 027 등)
├── terms*.html         # 이용약관
├── support*.html       # 고객 지원 페이지
├── apps/               # 앱별 상세 페이지
│   └── image-to-pdf/   # Image to PDF 앱 페이지
├── app-ads.txt         # 앱 광고 인증 파일
└── CNAME               # GitHub Pages 커스텀 도메인 설정
```

## 기술 스택

- **프론트엔드**: 순수 HTML, CSS (외부 프레임워크 없음)
- **폰트**: Google Fonts (Inter)
- **배포**: GitHub Pages

## 개발 규칙

- 빌드 도구가 필요 없는 정적 HTML/CSS 프로젝트
- 파일을 직접 수정하고 Git으로 푸시하면 자동 배포됨
- 새 앱 추가 시 해당 번호로 privacy/support/terms 페이지 생성
