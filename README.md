# 제목(Header)

<!-- html 에서의 h1 ~ h6 -->
<!-- markdown 문법이 html 문법으로 변환되어서 브라우저에 출력된다. -->

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

안녕하세요. 저는 개발자가 되기 위해
준비중인 박정훈 입니다.

# 줄바꿈(Line Breaks)

<!-- 띄어쓰기가 2번 이어져 있다면 줄바꿈으로 인식한다. -->
<!-- 그렇지 않은 경우에는 <br/> -->

안녕하세요. 저는 개발자가 되기 위해<br/>
준비중인 박정훈 입니다.

# 강조 (Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭_ + _두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

<!-- 들여쓰기 2번 하면 sub 목록으로 들어간다. -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하기 않음 옥록
- 순서가 필요하기 않음 옥록
- 순서가 필요하기 않음 옥록
  - 순서가 필요하기 않음 옥록
  - 순서가 필요하기 않음 옥록
- 순서가 필요하기 않음 옥록

# 링크(Links)

<!-- target 은 제공되지 않는다. 원시 html 방식으로 가능 -->

[GOOGLE](https://google.com)  
[GOOGLE](https://google.com 'Google로 이동')

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://www.notion.so/3b5088f485664e5d86c74eaf786d5382)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 중첩되는 인용문
>
> > 중첩되는 인용문
> >
> > > 중첩되는 인용문
> > >
> > > > 중첩되는 인용문

# 인라인(inline) 코드 강조

CSS 에서 `background` 혹은 `background-image` 속성으로 요소에 배경  
이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<div>hello</div>
```

```css
.list > li {
  position: absolute;
  left: 40px;
}
```

```javascript
function func() {
  const name = 'malza';
  return name;
}
```

<!-- $ 은 무시되는 부븐이고 그냥 터미널에 입력하는 부분이라고 알려주는것뿐-->

```bash
$ git commit -m "markdown"
```

```plaintext
어쩌고 저쩌고 이러쿵 저러쿵
```

# 표(Table)

<!-- 왼쪽 정렬 -->

position 속성

| 값       | 의미              | 기본값 |
| -------- | ----------------- | ------ |
| static   | 기준 없음         | 0      |
| relative | 요소 자신         | X      |
| absolute | 위치 상 부모 요소 | X      |
| fixed    | 뷰포트            | X      |

<!-- 가운데, 오른쪽 정렬 -->
<!-- : 을 어디에 붙이느냐에 따라 다르다. -->

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      0 |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

# 원시 HTML(Raw HTML)

안녕하세요. 저는 <u>개발자가</u> 되기 위해<br/>
준비중인 박정훈 입니다.

<a href="" target="_blank">NAVER</a>

# 수평선(Horizontal Rule)

---

---

---
