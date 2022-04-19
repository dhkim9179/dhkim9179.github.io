---
layout: post
title: Github Eclipse 연동
description: >
  Eclipse에서 Github를 연결해보자
sitemap: false
---

## Github 계정 생성

https://github.com 에 접속하여 계정을 생성한다.
 
## Github Repository 생성

1.  계정을 생성한 후 소스코드를 저장할 Repository를 생성한다.

![Full-width image](/assets/img/own/new_repository.png){:.lead width="800" height="100"}
Github Repository 생성 화면

2.  필수입력조건
*  Repository name: 사용할 Repository 명을 작성한다.
*  Public: 공개할 프로젝트이면 선택
*  Private: 공개하지 않을 프로젝트이면 선택

3. Create Repository를 클릭하여 Repository를 생성한다.
 
## Eclipse - Repository 연동

1.  Eclipse 실행
2.  Eclipse 상단 메뉴에 [Help] -> [Eclipse Marketplace] 선택
3.  Git 검색 후 [EGit] 설치
![Full-width image](/assets/img/own/eclipse-git.png){:.lead width="800" height="100"}
Eclipse Marketplace
4.  Eclipse 상단 메뉴에 [Windows] -> [Show View] -> [Other] -> [Git Repositories] 선택
5.  위에서 생성한 Repository로 이동하여 Https URL 주소 복사(https://github.com/dhkim9179/git-test.git)
6.  [Git Repositories] 에서 오른쪽 마우스 클릭 -> [Clone a Git Repository] 선택

위 화면처럼 URI에 아까 복사한 URL을 붙여넣으면 된다.
[Authentication]에 [User] 및 [Password]는 본인 Github 계정을 입력하면 된다.

만약, 로그인이 안되는 경우 Password 대신 Token 값을 입력하면 된다. (Token 생성방법: URL...)

7. [Next] -> [Next] -> [Finish] 클릭한다.

8. 프로젝트 연동
Github에 올릴 프로젝트 우클릭 -> [Team] -> [Share Project]

Git 선택 ..

