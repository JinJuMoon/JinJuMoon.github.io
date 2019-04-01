---
title: "How to make a jekyll blog on github pages"
date: 2019-03-31
tags: [jekyll, github, github pages, blog]
---

개인적으로 개발 공부를 시작하면서 이 과정들을 기록할 필요성을 느껴 블로그를 만들기로 했다. 개발자들의 블로그 주소가 github.io인 경우가 많아, 깃허브로 블로그를 만드는 법을 찾아보니 jekyll과 github pages를 활용하는 방법이 있어 도전하기로 했다! hexo도 있었지만 테마, 참조문서 등의 이유로 jekyll을 선택했다.

## 1. 개발환경 구축하기

- Homebrew 설치(맥OS용 패키지 관리자)
- Ruby 업그레이드(맥OS 내장 루비는 버전이 낮다)
- Rubygem 설치
- rbenv 설치
- jekyll 설치
- bundler 설치

## 2. 테마 선택하고 설치하기

- minimal_mistakes(깔끔하고 문서 설명이 잘 되어있어서 선택) - 사이트 적기
- 테마 설치방법 여러개 설명

참조문서 : minimal_mistaks 공식 페이지

## 3. 테마 커스터마이징하기

- config.yml(블로그 전반에 대한 환경설정)
- 언더바data > navigation.yml(about, posts 메뉴 생성) - 생성한 메뉴의 default를 config.yml에 추가해야한다.
- 언더바pages폴더 생성 후 마크다운 작성



references
1. [제킬 공식문서](http://jekyllrb)
