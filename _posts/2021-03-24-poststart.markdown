---
layout: post
title: 블로그 설정중 알게된것
date: 2021-03-24 22:40:00 +0900
category: note
---

공부중 오류를 잡거나 찾아봤더너 내용을 한곳에 모아놓기위해 블로그의 필용성을
느끼면서도 계속 미루다가 시작하게됨.

_config.yml 파일수정중 한글입력시 오류발생

```ruby
invalid byte sequence in utf-8
```
테마에 따라 한글오류 날수있을 가능성 확인후 테마를 변경하였으나 오류 계속됨

bundle install 실행시 bundler 업데이트요구
bundle update --bundler 실행

윈도우 메모장저장시 기본설정이 ansi형식이어서 에러발생
편집툴변경후 문제 없이 한글출력

깃 블로그 세팅 흐름
- 새로운 repository 생성 (아이디.github.io)
- 테마선택
- 선택된 테마 수정후
- 새로 만든 repository에 clone, add, commit, push


