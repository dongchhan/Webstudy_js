# Webstudy_js

## 1. 수업 소개 
- 선행: WEB1(HTML & Internet)  

- 사용자와 상호작용하는 웹 페이지를 위한 JS  
 
## 2. 수업의 목적
- 실습 목표: 웹 페이지 night/day 모드 구현  

- JS가 HTML을 제어하는 언어임을 실습 결과물을 통해 느껴봄  

## 3.HTML과 JS의 만남 : script 태그 
- `<script>여기에 JS 코드 작성</script>`  

- 정적인 HTML, 동적인 JS   
ex) 1+1 -> 1+1 vs 2

## 4.HTML과 JSㅢ 만남 : 이벤트
- html 안에서 특정 조건에 이벤트를 발생시키는 attribute
해당 attribute 뒤에는 JS 코드가 들어가도록 돼있음
- `<input type="button" value="hi" onclick="alert('hi')">`  
- `<input type="text" onchange="alert('changed')">`  
- `<input type="text" onkeydown="alert('key down!')">`  

## 5.HTML과 JS의 만남 : 콘솔 
- 브라우저 검사기 console 창에서 파일 생성 없이 JS 코드를 동작시켜볼 수 있음  
ex) 글자 수 세기 

- 검사기 Elements에서 esc키를 통해서 HTML 코드와 콘솔창을 함께 볼 수 있음  

- 페이스북 댓글 이벤트 당첨자 추첨 예시  

## 6.데이터타입 - 문자열과 숫자
- 데이터타입(자료형) ; Boolean, Null, Undefined, Number, String, Symbol  

- `str.length`
- `str.toUpperCase()`
- 등등의 여러 methods 체험 

## 7.변수와 대입 연산자 
- `var name = 'dongchan'`
- 문자열 내부 `"+변수명+"` 형식으로 변수 대입 가능 

## 8.웹브라우저 제어
- html은 정적인 언어라, 한번 작성된 형태에서 변경이 안된다. 
- JS를 통해 html을 변경시킬 수 있다. 

## 9-11.CSS 기초
__Agenda__
* CSS는 어떤 목적의 언어인가?
* CSS를 웹페이지에 삽입하는 방법은 무엇인가?
* style 속성은 무엇인가?
* 선택자가 무엇인가?
- 소스코드 웹페이지에 있음. 

## 9.CSS기초: Style 속성 
- `<h2 style="backgound-color:coral; color:powderblue">JavaScript</h2>`

## 10.CSS기초: Style 태그 
- CSS나 JS를 적용해주기 위해서 사용하는 어떠한 의미도 없는 HTML 태그 
- `<div></div>`: 줄바꿈 O
- `<span></span>`: 줄바꿈 X
- `<span style="font-weight:bold;">JavaScript</span>`

- Style 태그: Style 속성처럼 적용할 태그마다 일일히 작성하지 않아도 됨. 
- `<style></style>` 안에 CSS 작성 
- `js{"font-weight:bold; color:red;}` : 태그 명이 js인 태그에 적용 
- `.js{"font-weight:bold; color:red;}` : class가 js인 태그에 적용 

## 11.CSS기초: 선택자(Selector)
- `#first{color:green;}` : id가 first인 태그에 적용
- class와 달리 id는 유일해야함 
- 우선순위: id > class > tagname

## 12.제어할 태그 선택하기
- 

