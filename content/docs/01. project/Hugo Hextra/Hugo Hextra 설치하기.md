---
created: 2024-01-04 15:05
updated: 2024-01-04 17:04
date: 2024-01-04
tags:
  - Hugo
  - theme
  - Github
  - GithubPages
  - Git
  - Website
aliases:
  - 휴고
  - 테마
  - 깃허브
  - 깃허브페이지
  - 깃
  - 웹사이트
MOC: "[[09. MOC/Develop MOC]]"
title: Hugo Hextra 설치하기
weight: "3"
pre:
---
---

### 연결 문서
- 

### 메모
#### 스타터 템플릿 설치하기
설치 과정은 매우 간단합니다. [Hugo hextra 스타터 템플릿](https://github.com/imfing/hextra-starter-template)에 접속하여 스타터 템플릿을 사용해 새로운 저장소를 생성하세요. 
![새 저장소 만들기](https://i.imgur.com/9jFPxEp.png)

스타터 템플릿을 다운로드하지 않고 데모 테마의 리포지토리를 포크하여 배포하면 수정해야 할 부분이 있습니다. 하지만 제 개발 실력으로는 수정하는 것이 어려웠습니다. 따라서 설명서에서 요구하는 스타터 템플릿을 설치하는 것이 가장 간단하고 효과적인 방법입니다.

#### 원격 저장소 클론하기
휴고 파일을 관리할 폴더에서 터미널을 엽니다.
```terminal
git clone 자신의 리포지토리 주소
```
`git clone` 명령어를 사용하여 자신의 리포지토리 주소를 로컬과 연동합니다.

```terminal
hugo serve
```
hugo serve 명령어를 사용하여 헥스트라 휴고 테마를 확인합니다.

### 참조
-