---
layout: post
title: [Github] Eclipse 연동
description: >
  Eclipse에서 Github를 연결해보자
sitemap: false
---

## Eclipse Git Plugin 설치

![Full-width image](/assets/img/own/eclipse-git.png){:.lead width="800" height="100"}
Eclipse Marketplace
{:.figure}

1.  Eclipse 상단 메뉴에 [Help] -> [Eclipse Marketplace] 선택
2.  Git 검색 후 [EGit] 설치

## Eclipse Git Repository 셋팅

1. Eclipse 상단 메뉴에 [Windows] -> [Show View] -> [Other] -> [Git Repositories] 선택
2. Repository 셋팅

![Full-width image](/assets/img/own/git-repo.png){:.lead width="800" height="100"}
Setting git repositories
{:.figure}

  - Add an existing local Git repository
    - 기존에 존재하는 local Git repository를 추가한다.

  - Clone a Git repository
    - Github에 생성된 Repository를 불러온다.

  - Create a new local Git repository
    - 새로운 local Git repository를 생성한다.

## Github 계정 생성

https://github.com 에 접속하여 계정을 생성한다.
 
## Github Repository 생성

![Full-width image](/assets/img/own/new_repository.png){:.lead width="800" height="100"}
Github Repository 생성 화면
{:.figure}

1.  필수입력사항
*  Repository name: 사용할 Repository 명을 작성한다.
*  Public: 공개할 프로젝트이면 선택
*  Private: 공개하지 않을 프로젝트이면 선택

2. [Create Repository]를 클릭하여 Repository를 생성한다.
 
## Eclipse Git Plugin 설치

![Full-width image](/assets/img/own/eclipse-git.png){:.lead width="800" height="100"}
Eclipse Marketplace
{:.figure}

1.  Eclipse 상단 메뉴에 [Help] -> [Eclipse Marketplace] 선택
2.  Git 검색 후 [EGit] 설치

## Git Repository 셋팅

1. Eclipse 상단 메뉴에 [Windows] -> [Show View] -> [Other] -> [Git Repositories] 선택
2. Repository 셋팅

![Full-width image](/assets/img/own/git-repo.png){:.lead width="800" height="100"}
Setting git repositories
{:.figure}

  - Add an existing local Git repository: 기존 Git repository를 추가한다.
  - Clone a Git repository: Github에 생성된 Repository를 불러온다.
  - Create a new local Git repository: 새로운 local Git repository를 생성한다.



3. Local에서 Repository 생성 후 Github에 올리기

![Full-width image](/assets/img/own/git-clone.png){:.lead width="800" height="100"}
Eclipse Marketplace
{:.figure}

1.  Eclipse 상단 메뉴에 [Windows] -> [Show View] -> [Other] -> [Git Repositories] 선택
2.  위에서 생성한 Repository로 이동하여 Https URL 주소 복사(https://github.com/dhkim9179/git-test.git)
3.  [Git Repositories] 에서 오른쪽 마우스 클릭 -> [Clone a Git Repository] 선택

위 화면처럼 URI에 아까 복사한 URL을 붙여넣으면 된다.
[Authentication]에 [User] 및 [Password]는 본인 Github 계정을 입력하면 된다.

만약, 로그인이 안되는 경우 Password 대신 Token 값을 입력하면 된다. (Token 생성방법: URL...)

7. [Next] -> [Next] -> [Finish] 클릭한다.

8. 프로젝트 연동
Github에 올릴 프로젝트 우클릭 -> [Team] -> [Share Project]

Git 선택 ..

