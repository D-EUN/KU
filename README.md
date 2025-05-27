# E-BOOK Project

이 프로젝트는 EPUB 3.0 형식의 전자책을 구현한 것입니다. K-pop 소개와 고양이 비디오를 포함한 다양한 멀티미디어 콘텐츠를 제공합니다.

## 프로젝트 구조

```
E-BOOK/
├── book.epub          # 최종 EPUB 파일
├── mimetype          # EPUB 파일 형식 지정
├── META-INF/         # EPUB 메타데이터
│   └── container.xml # EPUB 컨테이너 정보
└── OEBPS/            # EPUB 콘텐츠
    ├── content.opf   # EPUB 메타데이터, 매니페스트
    ├── Text/         # XHTML 콘텐츠
    ├── Styles/       # CSS 스타일시트
    ├── Images/       # 이미지 파일
    ├── Video/        # 비디오 파일
    ├── Audio/        # 오디오 파일 (예정)
    ├── Fonts/        # 폰트 파일 (예정)
    └── Misc/         # 기타 파일
```

## 주요 기능

- K-pop 소개 페이지
- 고양이 비디오 콘텐츠
- 반응형 디자인
- 멀티미디어 지원 (이미지, 비디오)

## 기술 스택

- EPUB 3.0
- XHTML
- CSS
- JavaScript
- MP4 (H.264) 비디오
- JPG 이미지

## 파일 설명

### Text 디렉토리
- `page1.xhtml`: K-pop 소개 콘텐츠
- `animal.xhtml`: 고양이 비디오 콘텐츠
- `nav.xhtml`: EPUB 네비게이션 문서

### Styles 디렉토리
- `style1.css`: 메인 스타일시트
- `sgc-nav.css`: 네비게이션 스타일시트

### Images 디렉토리
- `bts.jpg`: BTS 그룹 이미지
- `blackpink.jpg`: BLACKPINK 그룹 이미지
- `video-poster.jpg`: 비디오 썸네일 이미지

### Video 디렉토리
- `20250429_Cat's_Sunny.mp4`: 고양이 비디오 파일

## 참고사항

- 모든 XHTML 파일은 UTF-8 인코딩을 사용합니다.
- 비디오 파일은 MP4(H.264) 포맷을 사용합니다.
- 이미지 파일은 JPG 포맷을 사용합니다.
- Audio와 Fonts 디렉토리는 향후 확장을 위해 준비되어 있습니다. "# KU" 
