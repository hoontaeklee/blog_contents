## 목차
<!-- TOC -->
- [요약](#%EC%9A%94%EC%95%BD)
- [Git 설치](#git-%EC%84%A4%EC%B9%98)
- [Hugo 설치](#hugo-%EC%84%A4%EC%B9%98)
- [Reference](#reference)

<!-- /TOC -->

## 요약
### 1. Git, Hugo 설치
### 2. Github 저장소 두 개 생성(컨텐츠, 웹사이트)
  - 이왕이면 한글 없는 경로 사용
### 3.

## Git 설치
### 1. [Git 홈페이지](https://git-scm.com/) 오른쪽 아래 초록 링크
### 2. cmd에서 `$ git --version` 실행 - 버전 잘 나오나 확인

## Hugo 설치
[Hugo 웹페이지](https://gohugo.io/getting-started/installing/#windows) 참고  

### 1.  C드라이브에 Hugo 폴더 생성
  - 블로그 관련 파일 저장
### 2. Hugo 폴더 안에 bin 폴더 생성
  - Hugo 관련 파일 저장
### 3. [Hugo 깃허브 저장소](https://github.com/gohugoio/hugo/releases)에서 최신 릴리즈 압축파일 다운로드
### 4. `C:/Hugo/bin`에 압축 해제
### 5. 환경변수에 `C:/Hugo/bin`추가
  - 윈도우 10: [여기](https://gohugo.io/getting-started/installing/#for-windows-10-users)를 참고
    - 윈도우키 - "환경" 검색 - "계정의 환경 변수 편집" - 유저 변수에서 `Path` 더블클릭 -  
새로만들기 - `C:/Hugo/bin`입력 - 확인
  - 환경변수를 추가하면 `C:/Hugo/bin` 외의 경로에서도 `C:/Hugo/bin`의 `hugo.exe` 사용 가능(=Hugo 기능 사용 가능)
### 6. cmd에서 `Hugo version`입력 - 버전 정보 맞게 나오면 굳

## Reference
- [Hugo로 Github.io 블로그 만들기](https://github.com/Integerous/Integerous.github.io/blob/master/README.md)
- [블로그 구축기 1 (Hugo + github.io)](https://ialy1595.github.io/post/blog-construct-1/)
