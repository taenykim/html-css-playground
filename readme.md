# 👋 Hello HTML, CSS

## Memo

연습목표기간 : 6/27 ~ 7/1

## Details

- HTML semantic ✅
- HTML op tag ✅
- HTML SEO ✅
- SPA SSR ✅
- css responsive
- css로 이모지만들어보기
- css animation
- css selector ✅
- css darkmode

## HTML semantic

시맨틱 HTML 마크업이 필요한 이유? : 태그별로 의미를 부여해줌으로써, 컴퓨터에게 (그리고 개발자에게도) 홈페이지의 요소요소를 의미를 알려주는 역할.

### 1. `<header>` `<footer>`

`<header>`에는 일반적으로 소개에 대한 내용이, `<footer>`에는 일반적으로 author, copyright, contact 내용이 들어간다.

### 2. `<nav>`

`<nav>` 에는 일반적으로 네비게이션 그룹(링크의 집합) 이 들어간다.

### 3. `<main>`

`<main>` 에는 일반적으로 메인 컨텐츠를 다룬다.

하나의 페이지에 하나만 존재해야 한다.

`<main>`의 자손으로 `<header>`, `<footer>`를 두지 않고

`<section>`과 `<article>`의 자손으로 `<main>`을 두지 않는다.

### 4. `<section>`

`<section>`은 하나의 구획을 의미한다. 일반적으로 주제에 따라 분류된 컨텐츠의 그룹으로 정의됨.

> A section is a thematic grouping of content, typically with a heading. -W3C

### 5. `<article>`

`<article>`은 독립적인 컨텐츠를 의미한다.

`<section>`과 `<article>`의 가장 큰 차이는 **"독립적으로 존재할 수 있는지"** 이다.

홈페이지에서 주제에 따라 분류된 컨텐츠들 (소개, 컨택트미, 내용)은 `<section>`을

블로그 포스팅이나 기사 등으로 독립적으로 사용되는 컨텐츠는 `<article>`을 쓴다.

### 6. `<h1>` `<p>`

제목(title)과 내용(description)이 존재하는 아티클에는 `<div>` 나 `텍스트노드` 대신 `<h1>`과 `<p>` 사용하기!

## og & meta tag

https://blog.naver.com/minisite/220717178399

## SSR in SPA

### 1. `<noscript/>`

You need to enable JavaScript to run this app.

자바스크립트로 페이지를 구성하는 spa의 특성 때문에 CSR이 사용되지 않거나 스크립트를 지원하지 않는 경우, 요 태그로 메시지를 적어준다.

### 2. 서버사이드 렌더링

https://www.postman.com/ 으로 request 날려보기!

## CSS selector Priority

https://ofcourse.kr/css-course/%EC%A0%81%EC%9A%A9-%EC%9A%B0%EC%84%A0%EC%88%9C%EC%9C%84

1. !important
2. inline style
3. id
4. class
5. tag
6. parent

> css는 위에서 아래로 적용하기 때문에 아랫것이 마지막으로 적용됨.(캐스캐이딩~) 클래스네임 지정 순서는 상관없음.