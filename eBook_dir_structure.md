# EPUB 3.0 전자책 디렉토리 구조

```
E-BOOK/
├── book.epub
├── mimetype
├── META-INF/
│   └── container.xml
└── OEBPS/
    ├── content.opf
    ├── Text/
    │   ├── page1.xhtml (K-pop 소개 페이지)
    │   ├── animal.xhtml (고양이 비디오 페이지)
    │   └── nav.xhtml (목차)
    ├── Styles/
    │   ├── style1.css (메인 스타일시트)
    │   └── sgc-nav.css (네비게이션 스타일시트)
    ├── Images/
    │   ├── bts.jpg
    │   ├── blackpink.jpg
    │   └── video-poster.jpg
    ├── Video/
    │   └── 20250429_Cat's_Sunny.mp4
    ├── Audio/
    ├── Fonts/
    └── Misc/
        └── script1.js
```

## 파일 설명

### 루트 디렉토리
- `book.epub`: 최종 EPUB 파일
- `mimetype`: EPUB 파일 형식 지정 (application/epub+zip)

### META-INF 디렉토리
- `container.xml`: EPUB 컨테이너 정보 및 content.opf 위치 지정

### OEBPS 디렉토리
- `content.opf`: EPUB 메타데이터, 매니페스트, 스파인 정의

#### Text 디렉토리
- `page1.xhtml`: K-pop 소개 콘텐츠
- `animal.xhtml`: 고양이 비디오 콘텐츠
- `nav.xhtml`: EPUB 네비게이션 문서

#### Styles 디렉토리
- `style1.css`: 메인 스타일시트
- `sgc-nav.css`: 네비게이션 스타일시트

#### Images 디렉토리
- `bts.jpg`: BTS 그룹 이미지
- `blackpink.jpg`: BLACKPINK 그룹 이미지
- `video-poster.jpg`: 비디오 썸네일 이미지

#### Video 디렉토리
- `20250429_Cat's_Sunny.mp4`: 고양이 비디오 파일

#### Misc 디렉토리
- `script1.js`: 자바스크립트 파일

## 참고사항
- Audio, Fonts 디렉토리는 현재 비어있음
- 모든 XHTML 파일은 UTF-8 인코딩 사용
- 비디오 파일은 MP4(H.264) 포맷 사용
- 이미지 파일은 JPG 포맷 사용 