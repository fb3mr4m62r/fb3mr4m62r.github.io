---
title: "테스트"
excerpt: "발췌테스트"
categories:
  - report
tags:
  - job
last_modified_at: 2019-05-06T01:30

---

5월7일 테스트

typora : 마크다운에디터
마크다운에디터로 작성후 웹용페이지를 보여주는 기능을 함

마크다운: HTML같은 문법

git : 폴더에서 미리보기를 할경우 상위폴더에가서 우클릭 girbash here 열고

터미널이 열리면 다움명령어로 미리보기가 가능하다 

 윈도우일경우에는 : /c/Windows/System32/chcp 65001 이명령어는 ANCI를 UTF-8로 변환하라는명령어

인데 해줘야함

`bundle exec jekyll serve`

로컬서버가 시작되면 

웹페이지에서 다음주소에서 확인가능

`localhost:4000`

확인후 gitbash 종료명령어 컨트롤 +씨 Yes



웹에 올리는 과정

깃배쉬상에서 pwd를 치면 현재 경로가 나오는데 내 블로그 최상위폴더에 위치해야함

여기서 명령어를 

`git status` 로 변환된것을 확인

`git add .` 로 변환된것을 인덱스에 올림

`git status` 로 인덱스된것을 확인해보면 변경된자료들이 녹색을변환되어잇음

`git commit -m "commit message"` :로컬 저장소에 변경사항저장

이제 서버에 올림

`git push`



끝 

 

Ruby: 프로그램랭귀지 

지킬 : 루비랭귀지로 만든 프로그램

지킬 : 블로그를 만드는 규칙 전반을 아우러서 관리하는 프로그램