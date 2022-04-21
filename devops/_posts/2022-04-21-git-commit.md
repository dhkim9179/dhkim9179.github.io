---
layout: post
title: [Github] Github Repository 연동 (1) 
description: >
  Github Repository에 연동해보자
sitemap: false
---

## Github Repository 연동 (1)

Github Repository에 연동할 수 있는 방법은 두 가지가 있다.

1. 로컬 저장소에서 연동하기
2. 원격 저장소에서 연동하기
 
## 로컬 저장소에서 연동하기

1. Repository로 사용할 폴더를 생성하고, 폴더 내 파일을 하나 생성한다.
2. Windows 또는 Linux 커맨드 창을 열고, 해당 폴더로 이동한다.
3. Github 계정을 연동한다.

```
git config --global user.email "[Github 이메일주소]" 
git config --global user.name "[Github 아이디]"
```

초기설정

```
git init
git add .
```

파일 커밋하기

```
git commit -m "comment"
```

파일 올리기(push)

```
git push origin [branch name]
```

파일 받아오기(pull)

```
git pull origin [branch name]
```

## 원격 저장소에서 연동하기

1. Windows 또는 Linux 커맨드 창을 열고, Repository를 받아올 폴더로 이동한다.
2. 원격으로 저장소를 받아온다.

```
git clone [Repository 주소]
```

파일 커밋하기

```
git commit -m "comment"
```

파일 올리기(push)

```
git push origin [branch name]
```

파일 받아오기(pull)

```
git pull origin [branch name]
```