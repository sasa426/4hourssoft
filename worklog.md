# Work Log

## 2026-11-10
### Rename 중개콩 → 공중콩 in privacy015.html
- **Purpose**: 앱 이름이 2026-11-08에 '공중콩(GongjungKong)'으로 바뀌어 개인정보처리방침의 앱 이름 표기를 맞춤
- **Details**:
  - `privacy015.html`의 '중개콩' 4곳 → '공중콩', 'JunggaeKong' 4곳 → 'GongjungKong' (제목·배지·요약·본문 제1조·영문 제1조)
  - 앱 ID `com.sasa.junggaekong`과 URL(https://4hourssoft.com/privacy015.html)은 변경 없음
- **Status**: Completed

## 2026-11-07
### Create Privacy Policy Page for 중개콩 (JunggaeKong)
- **Purpose**: 앱 스토어 등록에 필요한 개인정보처리방침 공개 URL 제공을 위해 `privacy015.html` 생성
- **Details**:
  - 개인정보를 수집·저장·전송하지 않는 완전 오프라인 앱임을 명시 (서버·제3자 SDK·기기 권한 없음, 학습 기록은 기기 안에만 저장)
  - 한국어 기본, 영어 전환 지원 (privacy013.html의 언어 전환 방식 재사용)
  - URL: https://4hourssoft.com/privacy015.html
- **Status**: Completed

## 2026-02-12
### Add Multi-language Support to support013.html
- **Purpose**: support013.html 페이지에 5개 언어(영어, 스페인어, 일본어, 중국어, 한국어) 지원 추가
- **Details**:
  - 언어 선택 UI를 5개 버튼으로 확장 (English, Español, 日本語, 中文, 한국어)
  - 반응형 디자인 적용 (모바일 최적화)
  - 각 언어별 완전한 콘텐츠 섹션 추가 (데이터 삭제 방법, FAQ 등)
  - JavaScript 로직 업데이트하여 모든 언어 전환 지원
  - 기본 언어: 영어
- **Status**: Completed

### Create Data Deletion Support Page for Can We Play?
- **Purpose**: Google Play Console에서 요구하는 데이터 삭제 URL을 제공하기 위해 `support013.html` 파일 생성
- **Details**: 
  - Can We Play? 앱의 데이터 삭제 요청 방법을 명시 (앱 내 설정 > 회원 탈퇴, 이메일 요청)
  - 한국어/영어 이중 언어 지원 (기본: 영어)
  - URL: https://4hourssoft.com/support013.html
- **Status**: Completed

## 2026-02-01
### Commit and Push Changes
- **Purpose**: Save changes including the new generic `support.html` and the generalized `privacy.html`.
- **Status**: Completed

### Generalize Privacy Policy
- **Purpose**: Update `privacy.html` to remove specific app branding and create a generic privacy policy applicable to all applications.
- **Status**: Completed

### Create Generic Support Page
- **Purpose**: Create a generic `support.html` page without specific app branding to serve as a common support portal.
- **Status**: Completed

## 2026-01-24
### Commit and Push Changes
- **Purpose**: Save recent changes to privacy policies, terms, and project documentation (CLAUDE.md, index.html, privacy*.html).
- **Status**: Completed
