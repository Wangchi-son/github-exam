# 마크다운 문법 학습하기

## 강조(Emphasis)

이텔릭체는 _별표(asterisks)_ 혹은 _언더바(underscore)_ 를 사용하세요.  
두껍게는 **별표(asterisks)** 혹은 **언더바(underscore)** 를 사용하세요.  
***이텔릭체*와 두껍게**를 같이 사용할 수 있습니다.  
취소선은 ~~물결표시(tilde)~~ 를 사용하세요.  
줄바꿈은 스페이스바 두번  
<u>밑줄</u>은 `<u></u>`를 사용하세요

## 목록(List)

#### 라면 끓이는 법(ol)

---

1. 라면을 구입
1. 물을 끓인다
1. 라면을 넣는다
1. 맛있게 끓인다
1. 맛있게 먹는다

#### 과일 목록(ul)

---

- 사과
- 딸기
- 파인애플
- 망고

## 링크(Link)

##### blank 기능 지원X - 사용하려면 a태그

---

[네이버](https://www.naver.com/)에 [마크다운(Markdown)](https://heropy.blog/2017/09/30/markdown/)을 검색해 보세요.

[구글][google link]

[google link]: https://www.google.com/

## 이미지(Images)

---

![대체 텍스트](https://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요")

## 링크 이미지(Link Images)

---

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)

## 인라인 코드강조

---

저는 `background`속성과 `position: absolute;`를 적용했습니다.

## 블록 코드강조

---

```html
<a href="https://www.google.co.kr/" target="_black">GOOGLE</a>
```

```css
#markdown {
  position: absolute;
  margin: 10px;
  width: 150px;
}
```

```js
function hello() {
  return {};
}
```

## 표

---

|         값 | 의미                                     |
| ---------: | ---------------------------------------- |
| `relative` | **자신**을 기준으로 배치                 |
| `absolute` | **부모 요소의 position값** 기준으로 배치 |
|    `fixed` | **브라우저 창**을 기준으로 배치          |

## 인용문

---

> 여기에 인용문을 삽입하세요!
>
> > 두번째 줄 인용문 삽입!

## 원시 HTML

---

<blockquote>원시 HTML 인용문!</blockquote>

<u>마크다운에서 지원하지 않는 기능</u>을 사용할 때 유용하며, 대부분 잘 동작합니다.

<img width="150" src="https://www.gstatic.com/webp/gallery/4.jpg" alt="Prunus" title="A Wild Cheery (Prunus avium) in flower">
