---
layout: post
title: [Github] Eclipse 연동
description: >
  Eclipse에서 Github를 연결해보자
sitemap: false
---

## Github Repository 연동 (2)

Eclipse에서 Github Repository에 연동한다.

## Eclipse git plugin 설치

1.  Eclipse 상단 메뉴에 [Help] -> [Eclipse Marketplace] 선택
2.  Git 검색 후 [EGit] 설치

![Full-width image](/assets/img/own/eclipse-git.png){:.lead width="800" height="100"}
Eclipse Marketplace
{:.figure}

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

## 원격 저장소 연결하기

[Clone a git repository] 선택

![Full-width image](/assets/img/own/git-clone.png){:.lead width="800" height="100"}
Clone a git repository (1)
{:.figure}

  - URI 입력
  - User: Github 계정 ID 입력
  - Password: Github 계정 비밀번호 또는 Token 입력

[Next]

![Full-width image](/assets/img/own/git-clone2.png){:.lead width="800" height="100"}
Clone a git repository (2)
{:.figure}

[Finish]

![Full-width image](/assets/img/own/git-clone3.png){:.lead width="800" height="100"}
Clone a git repository (3)
{:.figure}

[원격 저장소 연결완료]

![Full-width image](/assets/img/own/git-clone4.png){:.lead width="800" height="100"}
Clone a git repository (4)
{:.figure}