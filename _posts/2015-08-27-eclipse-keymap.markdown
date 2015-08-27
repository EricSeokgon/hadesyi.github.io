---
layout| post
title| "Eclipse 단축키"
description| "Eclipse 단축키"
date| 2015-8-27
category: blog
tags: [eclipse, keymap]
---

<!-- <div id="toc"><p class="toc_title">목차</p></div> -->
* TOC
{:toc}

# 윈도우즈 이클립스 단축키
-  기본적으로 Preference > General > Keys에서 대부분(모든)의 단축키 확인 가능합니다.

## 거의 달고 사는 단축키

|단축키|설명|
|-----|----|
|Ctrl+Shift+L | 단축키 보기 Hint|
|Ctrl + s | 저장 및 컴파일|
|ctrl + i | 소스 깔끔 정리(인덴트 중심의 자동구문정리)|
|ctrl + space | 어휘의 자동완성(Content Assistance)|
|ctrl + 1 | Quick Fix(Rename에 주로 사용)|
|ctrl + shift + M | 캐럿이 위치한 대상에 필요한 특정클래스 import|
|ctrl + shift + O | 소스에 필요한 패키지의 자동 임포트|
|ctrl + / | 한줄 또는 선택영역 주석처리/제거|
|ctrl + Q | 마지막 편집위치로 가기|
|ctrl + L | 특정줄번호로 가기|
|ctrl + D | 한줄삭제|
|ctrl + H | Find 및 Replace|
|ctrl + K | 다음찾기(또는, 찾고자 하는 문자열을 블럭으로 설정한 후 키를 누른다.)|
|ctrl + shift + K | 이전찾기(또는, 찾고자 하는 문자열을 블럭으로 설정한 후 역으로 찾고자 하는 문자열을 찾아감.)|
|alt + shift + j | 설정해 둔 기본주석 달기|
|Ctrl + 객체클릭(혹은 F3) | 클래스나 메소드 혹은 멤버를 정의한 곳으로 이동(Open Declaration)|

## 사용하면 유용한 단축키

|단축키|설명|
|-----|----|
|ctrl + shift + f | 소스 깔끔 정리
|ctrl + 2 + R | Rename(리팩토링)
|ctrl + shift + / | 선택영역 block comment 설정
|ctrl + shift + \ | 선택영역 block comment 제거
|alt + shift + up | Enclosing Element 선택(괄호의 열고 닫기 쌍 확인에 유용함)
|ctrl + O | Outline창열기
|Alt + ->, Alt + <- | 이후, 이전
|해당프로젝트에서 alt + enter | Project 속성
|sysout > Ctrl + Space | System.out.println();
|try > Ctrl + Space | 기본 try-catch문 완성
|for > Ctrl + Space | 기본 for문 완성
|템플릿을 수정,추가 | Preferences > java > editor > Templates

## 알고 있으면 아는척좀 할 수 있는 단축키

|단축키|설명|
|-----|----|
|ctrl + N | 새로운 파일 및 프로젝트 생성
|ctrl + shift + s | 열려진 모든파일 저장 및 컴파일
|alt + / | Word Completion
|alt + shift + R | Rename
|ctrl + shift + G | 특정 메써드나 필드를 참조하고 있는 곳을 찾는다.
|ctrl + shift + B | 현재커서위치에 Break point설정/해제
|ctrl + alt + R
|ctrl + f11 | 실행
|f11 | 디버깅 시작
|f5 | step into
|f6 | step over
|f8 | 디버깅 계속
|ctrl + . | 다음오류부분으로 가기
|ctrl + , | 이전오류부분으로 가기
|f12 | 에디터로 커서이동
|ALT + UP,DOWN | 현재 줄 위치 이동
|Ctrl + j | 검색할 단어를 입력하면서 실시간으로 검색
|Ctrl + Shift + j | 검색할 단어를 입력하면서 실시간으로 거꾸로 검색
|F4 | 클래스명을 선택하고 누르면 해당 클래스의 Hierarchy 를 볼 수 있다.
|ctrl + alt + up/down | 한줄 duplicate
|alt + shift + 방향 | 선택
|ctrl + shift + g | 케럿이 위치한 객체가 참조 되는 곳을 찾아 준다
 
 

## 실행

|단축키|설명|
|-----|----|
| Ctrl + F11 | 바로 전에 실행했던 클래스 실행
 
## 소스 네비게이션 

|단축키|설명|
|-----|----|
| Ctrl + 마우스커서(혹은 F3) | 클래스나 메소드 혹은 멤버를 상세하게 검색하고자 할때
| Alt + ->, Alt + <- | 이후, 이전
| Ctrl + o | 해당 소스의 메소드 리스트를 확인하려 할때
| F4 | 클래스명을 선택하고 누르면 해당 클래스의 Hierarchy 를 볼 수 있다.

## 문자열 찾기 

|단축키|설명|
|-----|----|
| Ctrl + k | 찾고자 하는 문자열을 블럭으로 설정한 후 키를 누른다.
| Ctrl + Shift + k | 역으로 찾고자 하는 문자열을 찾아감.
| Ctrl + j | 입력하면서 찾을 수 있음.
| Ctrl + Shift + j | 입력하면서 거꾸로 찾아갈 수 있음.
| Ctrl + f | 기본적으로 찾기
 
## 소스 편집

|단축키|설명|
|-----|----|
| Ctrl + Space | 입력 보조장치(Content Assistance) 강제 호출 => 입력하는 도중엔 언제라도 강제 호출 가능하다.
| F2 | 컴파일 에러의 빨간줄에 커서를 갖져다가 이 키를 누르면 에러의 원인에 대한 힌트를 제공한다.
| Ctrl + l | 원하는 소스 라인으로 이동 로컬 히스토리 기능을 이용하면 이전에 편집했던 내용으로 변환이 가능하다.
| Ctrl + Shift + Space | 메소드의 가로안에 커서를 놓고 이 키를 누르면 파라미터 타입 힌트를 볼 수 있다.
| CTRL + D|한줄 삭제 
| CTRL+W|파일 닫기 | 
| CTRL+I |들여쓰기 자동 수정. (3.0 NEW) | 
| 블록 주석(/*..*/) 추가.(3.0 NEW)| CTRL+SHIFT+/
| Ctrl + / |해주면 여러줄이 한꺼번에 주석처리됨. 주석 해제하려면 반대로 하면 됨.
|ALT+UP(DOWN)|위(아래)줄과 바꾸기 | 
| ALT+SHIFT+방향키|블록 선택하기.  | 
| CTRL+SHIFT+SPACE|메소드의 파라메터 목록 보기. | 
| CTRL+SHIFT+O|자동으로 import 하기 | 
|  CTRL + SHIFT + F4|열린 파일 모두 닫기 |
| CTRL+SHIFT+|블록 주석 제거 | 
| CTRL+M|전체화면 토글 | 
| 한Ctrl + Alt + 위(아래)|줄(블럭) 복사 | 
|  Ctrl + , or .|다음 annotation(에러, 워닝, 북마크 가능)으로 점프 |
| Ctrl + 1  |퀵 픽스 | 
| F3|메소드 정의부로 이동 | 
| Ctrl + T |하이어라키 팦업 창 띄우기(인터페이스 구현 클래스간 이동시 편리) | 
| CTRL + O |메소드나 필드 이동하기 
| CTRL+F6 | ULTRAEDIT나 EDITPLUS 의 CTRL+TAB 과 같은 기능. | 
 
## 템플릿 사용
1. sysout 입력한 후 Ctrl + Space 하면 System.out.println(); 으로 바뀐다.
2. try 입력한 후 Ctrl + Space 하면 try-catch 문이 완성된다.
3. for 입력한 후 Ctrl + Space 하면 여러가지 for 문을 완성할 수 있다.
4. 템플릿을 수정하거나 추가하려면 환경설정/자바/편집기/템플리트 에서 할 수 있다.
 
## 메소드 쉽게 생성하기
1. 클래스의 멤버를 일단 먼저 생성한다.
2. override 메소드를 구현하려면 | 소스->메소드대체/구현 에서 해당 메소드를 체크한다.
3. 기타 클래스의 멤버가 클래스의 오브젝트라면 | 소스->위임메소드 생성에서 메소드를 선택한다.


## 소스 코드 형식 및 공통 주석 설정 
1. 환경설정 -> 자바 -> 코드 스타일 -> 코드 포멧터 -> 가져오기 -> 프로파일.xml 을 불러다가 쓰면 된다.
2. 또한 다수의 자바파일에 프로파일을 적용하려면 패키지 탐색기에서 패키지를 선택한 후 소스 -> 형식화를 선택하면 된다.
3. 환경설정 -> 자바 -> 코드 스타일 -> 코드 템플리트 -> 가져오기 -> 템플리트.xml 을 불러다가 쓰면 된다.

## 에디터 변환
1. 에디터가 여러 파일을 열어서 작업중일때 Ctrl + F6 키를 누르면 여러파일명이 나오고 F6키를 계속 누르면 아래로
|단축키|설명|
|-----|----|
|Ctrl + Shift + F6| 키를 누르면 위로 커서가 움직인다.
|Ctrl + F7 | 뷰간 전환
|Ctrl + F8 | 퍼스펙티브간 전환
|F12 | 에디터로 포커스 위치