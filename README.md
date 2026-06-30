# MD메모장 — Markdown Notepad PWA

마크다운 에디터 웹앱. 라이브 미리보기, 7가지 테마, 5단계 UI 크기, .md 파일 열기/저장을 지원합니다.

## 파일 구성

```
md-notepad/
├── index.html      # 앱 본체 (HTML + CSS + JS 일체형)
├── manifest.json   # PWA 메타데이터
├── sw.js           # Service Worker (오프라인 캐시)
├── icon-192.png    # PWA 아이콘 (192×192)
└── icon-512.png    # PWA 아이콘 (512×512)
```

## 배포 방법 (GitHub Pages)

1. GitHub에서 새 레포지토리 생성
2. 이 폴더의 파일을 모두 업로드
3. Settings → Pages → Source: `main` 브랜치 루트(`/`) 선택
4. 잠시 후 `https://<username>.github.io/<repo>/` 로 접속

## 앱 설치 (PWA)

배포 URL 접속 후:
- **Chrome/Edge**: 주소창 우측 설치 아이콘 클릭
- **Android**: 브라우저 메뉴 → "홈 화면에 추가"
- **iOS Safari**: 공유 버튼 → "홈 화면에 추가"
- **앱 내 설치 버튼**: 타이틀바의 "설치" 버튼 클릭

설치 후에는 오프라인에서도 동작합니다.

## 기능

- 좌우 분할 — 편집 + 라이브 미리보기
- 툴바 — 굵게/기울임/취소선/코드/제목/목록/표 등
- 7가지 테마 — 라이트, 다크, Claude, Duolingo, GitHub, Kakao, Nintendo
- 5단계 UI 크기 조절 (기본 2단계)
- .md 파일 열기 / 저장
- 단축키: Ctrl+S(저장), Ctrl+O(열기), Ctrl+B(굵게), Ctrl+I(기울임)
