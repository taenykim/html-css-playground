# 👋 Hello HTML, CSS

## Memo

연습목표기간 : 6/27 ~ 7/1

## Details

- HTML semantic ✅
- HTML op tag ✅
- HTML SEO ✅
  ├─ SPA SSL
- css responsive
- css로 이모지만들어보기
- css animation
- css selector
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
