---
layout: post
title: "#1 HTML 이란 무엇인가?"
subtitle: "HTML이란"
category: frontend
tags: html
# image:
#   path: /assets/img/2022-09-16/ark68.png
---

<!--> TABLE OF CONTENTS <!-->
* this unordered seed list will be replaced by the toc
{:toc}

## HTML 이란 무엇인가

> HTML 은 `Hyper Text Markup Language` 약어로 HyperText(웹 페이지에서 다른 페이지로 이동할 수 있도록 하는 것) 기능을 가진 문서를 만드는 언어입니다.
  다시 말해, 구조를 설계할 때 사용되는 언어로 hyper link 시스템을 가지고 있으며, 흔히 말하는 웹 페이지를 위한 마크업 언어라고 할 수 있습니다.

## 소개

{:.text-align-center}
![Ark 1](/assets/img/2023-07-12/html.png){:width="90%", height="100%"}
<!-- ![Ark 2](/assets/img/2022-09-16/my-ark-2.jpg){:width="45%"} -->

간단히 `웹(Web)`이라 부르는 경우가 많습니다.
이 문서도 역시 엄연한 웹 페이지이며, 따라서 현재 이 문서를 읽고 있다면 '웹 페이지를 보고 있다'고도 할 수 있습니다.
그리고 이 `web` 이란 용어는 인터넷과 동의어로 쓰이는 경우가 많으나 엄격히 말해 서로 다른 개념입니다.
인터넷이란 이름은 `네트워크의 네트워크`를 구현하여 모든 컴퓨터를 하나의 통신망 안에 연결(Inter Network)하고자 하는 의도에서
이를 줄여 `인터넷(Internet)`이라고 처음 명명하였던데 어원을 두고 있습니다.
이러한 개념들을 상세히 숙지하고 있을 필요는 없지만 이 분야를 공부하고자 한다면 배경 지식정도는 알아두면 좋을 것 같습니다.

또한 앞으로 이 마크업 언어를 숙지하는데 있어 항상 시멘틱 마크업을 목표로 나아가야 할 것입니다.
시멘틱 마크업(Semantic Markup) 은 웹 사이트(페이지)의 콘텐츠를 설명하는데 사용되는 마크업 언어이고,
HTML 은 콘텐츠의 의미를 설명하는데 유일한 목적을 가집니다.
앞으로 공부할 CSS 가 비주얼 디자인(Visual Design) 이라면 HTML 은 구조적 설계(Structure Design) 이라 할 수 있습니다.

## HTML요소의 구조와 속성

HTML은 이름에서도 알 수 있듯이 마크업(MarkUp) 언어입니다!<br/>
한마디로 프로그래밍 언어가 아니라는거죠!<br/>
<u>문서의 구조(뼈대)</u>라고 보시면 되겠습니다.

다음 문장을 예시로 들어볼까요? <br/>
`<p style="color:red;">Hyper Text Markup Language</p>`
1. 여는 태그(Tag) : `p`라는 요소의 이름과 요소의 효과를 적용시킵니다.
2. 속성명(attribute) : `style` 요소의 속성을 의미합니다.
3. 속성값(attribute value) : `color:red;` 요소의 속성 값을 의미합니다. <u>색깔을 빨간색으로</u>라는 의미를 부여합니다.
4. 값(value) : `Hyper Text Markup Language` 요소의 내용을 의미합니다.
5. 닫는 태그(tag) : `</p>` 항상 시작이 있으면 끝이 있어야겠죠? `/`로 마무리 해줍니다. 

보통 모든 태그들은 시작과 끝이 존재합니다. 하지만 예외의 태그도 존재합니다.
`</br>` 이러한 br 태그처럼 닫는 태그가 따로 존재하지 않고 하나의 태그에 열고 닫는태그가 같이 있는 태그를 `빈(empty)태그`라고합니다.

## HTML 기본뼈대(실습)

저희는 Markup언어를 배워보았습니다. 그러면 실제로 한번 만들어 봐야겠죠?<br/>
만드는 방법은 쉽습니다~<br/>
1 먼저 바탕화면에 우클릭 후 새로만들기로 txt 파일을 만들어주세요!<br/>
2 다음 아래와 같은 코드를 복사해서 붙여주세요!<br/>

```
<html>
  <head>
	  문서의 정보, 화면상에 출력되지는 않는다.
  </head>
  <body>
    	화면상에 보여지는 모든 요소를 위치한다.
  </body>
  <footer>
    하단 CopyRight부분에 위치한다.
  </footer>
</html>
```

3 파일을 저장하고 확장자명 `txt`를 `html`로 바꿔주세요!<br/>
4 `.html`확장자 파일을 열어주시면 <u>정적(static) 웹 페이지</u>가 만들어집니다!<br/>