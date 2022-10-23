---
title : Markdown 사용법 정리
date : 2022-10-23
categories : [Github, Creating a page]
tags : [markdown, form]
toc : true
math : true
---
# 마크다운(Markdown) 사용법 정리
내가 보기 위해 만든 페이지

<!-- 마크다운 양식 -->
- 마크다운 양식
===

---

>
```
---
title : Basic Form
date : 2022-10-21
categories : [Github, creating a page]
tags : [Markdown, Form]
toc : true
math : true
---
```

<br>
<!-- 제목 -->
- 제목 쓰기 
===

---
>
# #제목1
## ##제목 2
### ###제목 3
#### ####제목 4
##### #####제목 5
###### ######제목 6

>
<big>또는</big>
```
제목 1
===
제목 2
---
```

<br>
<!-- 텍스트 쓰기 -->
- Text 쓰기
===

---
```
글쓰기 : 그냥 쓰면 됨 or <body>
엔터   : Enter 또는 <br> 또는 띄어쓰기 두번
구분선 : --- 또는 ***
```

<br>
<!-- 텍스트 강조 -->
- 텍스트 강조
===

---
```
진하게 : __진하게__ 또는 **진하게**
기울임 : _기울임_ 또는 *기울임*
취소선 : ~~취소선~~
밑줄   : <u>밑줄</u>
```

>
__\_\_진하게\_\___  
_\_기울임\__  
~~(\~\~취소선\~\~)~~  
<u>밑줄</u>

<br>
<!-- 텍스트 스타일 -->
- 텍스트 스타일
===

---
```
형광   : <mark> 내용 </mark>
스타일 : <span style="font-size: 14px; color: green">크기는 12px이고 색상은 초록색인 텍스트</span>
글자 크기 : <span style="font-size:150%">텍스트</span>
수식 가운데 맞춤 : <div class="text_center">수식</div>    : 원래는 텍스트도 되던데 왜 수식만 되지.. 수식에 span으로 스타일 변경할때 유용함
```
>
<mark>형광</mark><br>
<span style="font-size: 14px; color: green">크기는 12px이고 색상은 초록색인 텍스트</span><br>
<span style="font-size:150%">텍스트</span><br>
<div class="text_center"><span style="font-size:300%">$$f=ma$$</span></div>

<br>
<!-- 링크 삽입 -->
- 링크 삽입
===

---
```
링크 삽입   : <링크>
인라인 링크 : [내용](링크)
```
><https://DongMinM.github.io/dongmin>  
[블로그 링크](https://DongMinM.github.io/dongmin)

<br>
<!-- 인용문 -->
- 인용문
===

---
```
> or >>
```

> 이거
>> 이거

<br>
<!-- 인라인 블럭 -->
- 인라인 블럭
===

---

```
`(내용)`
또는
```(엔터)(내용)(엔터)```   
```

>
`내용`
```
내용
```

<br>
<!-- 코드 박스 -->
- 코드 박스
===

---
```
```(언어)
코드
```. (마지막 . 제외)
```

>
```python
int a = 3
```

<br>
<!-- 수식 표현 -->
- 수식 표현
===

---

```
$$
1. dot 표현 : m\ddot{u}(t)+c\dot{u}(t)+ku(t)=p(t)  (d의 갯수만큼 표현됨)
$$
```
>
$$
1. \;\; m\ddot{u}(t)+c\dot{u}(t)+ku(t)=p(t)
$$

<br>
<!-- 행렬 표현 -->
- 행렬 표현
===

---

```
$$
\begin{bmatrix} 1&0\\0&1\\  \end{bmatrix}
\begin{pmatrix} 1&0\\0&1\\  \end{pmatrix} =  
\begin{bmatrix} 1&0\\0&1\\  \end{bmatrix}  
$$
```
>
$$
\begin{bmatrix} 1&0\\0&1\\  \end{bmatrix}
\begin{pmatrix} 1&0\\0&1\\  \end{pmatrix} = 
\begin{bmatrix} 1&0\\0&1\\  \end{bmatrix}
$$


