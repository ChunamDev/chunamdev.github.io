---
layout: post
title:  "Sublime Text"
date:   2018-04-10
categories: Sublime Text
img:
categories: [sublime text, editor]
---

##  Sublime Text2 설치 및 세팅

### Sublime Text2 설치

1. Sublime Text2 Download [http://www.sublimetext.com/2](http://www.sublimetext.com/2)

2. 각자 OS에 맞는 파일을 다운로드 ![](http://)

3. Sublime Text 2를 실행한후 ctrl+\` 또는 `View > Show Console` 을 열고 다음단계의 내용을 복사 => 붙여넣기 => 엔터

4. `Package Control 설치하기` [SUBLIME TEXT 2 Package Control](https://packagecontrol.io/installation#st2)

5. Sublime 재부팅 후 `ctrl + shift + p => install package 입력 후 엔터`

6. 각종 플러그인 설치
  - `IMESupport` 한글 입력을 할 때 한글자씩 늦게 보이는 현상을 완화시켜준다. Only Window
  - `ConvertToUTF8` 서브라임 텍스트는 euc-kr 을 지원하지 않는데, 이 플러그인을 깔고 File - Set File Encoding To 에서 EUC-KR을 선택하면 된다.
  - `BracketHighlighter` 태그의 처음과 끝을 하이라이트 시켜서 코드 가독성을 높여준다.
  - `AdvancedNewFile` 단축키로 원하는 경로에 파일을 생성해준다. lorem\test.html 식으로 입력하면 한번에 생성되고 폴더가 없으면 생성된다.
  - `JQuery `  JQuery 자동완성 기능이 추가된다.
  - `CSS Format`  css 를 여러가지 방법으로 정렬시켜준다.
  - `CSScomb` css 의 속성 순서를 원하는 순서로 변경시켜준다. CSSFormat 과 같은 기능도 있다.
  - `View in Browser`  chrome, firefox, safari, IE 등 여러 브라우저로 오픈 가능하고 상대 경로도 가능
  - `Prefixr` Cross browser를 지원하는 플러그인이다. 하나의 CSS를 작성하면 자동으로 Cross browser에 맞게 CSS를 생성해 준다.
  - `HTML-CSS-JS Prettify` HTML, CSS, JS에 대해서 코딩을 이쁘게 정렬해주는 기능을 제공해 준다. `Ctrl + Shift + H` 키를 누르면 코드가 이쁘게 정렬된다.
  - `FuzzyFilePath` 이미지나 파일의 경로를 자동으로 알려주는 플러그인
  - `Markdown Preview` 작성하다가 최종 결과물이 보고 싶다면 `CTRL + B`(빌드. 윈도)하면 브라우저에 작성하고 있는 문서가 보여질 것이다.