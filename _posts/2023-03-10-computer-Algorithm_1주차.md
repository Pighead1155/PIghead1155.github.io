---
layout: post
title:  "Computer algorithm 1주차"
date:   2023-03-10 10:08:05 +0900
categories: jekyll update
---
# Computer algorithm 1주차

Jekyll 사용법

1. Ruby 설치하기 (chcp 65001 입력하기)
2. Jekyll, Bundler 설치하기
3. jekyll new PATH 명령어로 폴더 새로 생성
4. 해당 폴더로 이동 cd PATH
5. Jekyll 실행 bundle exec jekyll serve
------------------------------------------------------------
블로그 포스팅

1. 해당 폴더 _posts 이동
2. (마크다운.md/.markdown) 파일 생성(포맷 : 년-월-일-파일이름.md)
3. 마크다운 편집
  (1) yaml을 이용해서 포스트 속성 설정(제목, 날짜, 레이아웃, 카테고리)
  (2) 포스트 작성(markdown 문법 활용)
------------------------------------------------------------
Git, Github

명령어
프로젝트 생성 시 - 
1. init : git init . 현재 폴더를 git 저장소로 변환
1.1 github로 사용하기
2. clone : git clone 원격저장소 로컬저장소 데이터 저장소 만들기(최초 1회) 

버전 업데이트 시 (소스코드 수정 / 파일 생성) -
3. add : git add ( . ) : 파일 추가(스테이징)
- 여러 개 필요할 시 띄어쓰기 후 파일 입력. 
4. commit : git commit -m "message"  버전 업데이트
5. push : git push 데이터 올리기

주의점
x.c
A : 1.3.1 버전 > 수정 131번 줄 a=3 > push
B : 1.3.1 버전 > 수정 131번 줄 b=7 > push
>> 충돌이 일어난다.(같은 줄) 
충돌이 날 부분을 잘 찾고 건드려야 함. - branch(가지)작업으로 충돌을 미연에 방지하려고 함.
------------------------------------------------------------
Github : pages(개인 웹서버)
