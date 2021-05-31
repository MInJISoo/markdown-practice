# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6


# 문장 (Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세


# 줄바꿈 (Line Breaks) - 띄어쓰기 두번 / <br/>

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세   
무궁화 삼천리 화려 강산 <br/>
대한 사람 대한으로 길이 보전하세  


# 강조 (Empasis)

_이텔릭체_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  


# 목록 (List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(들여쓰기 2번/ 띄어쓰기 4번)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록\


# 링크(Link)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)



<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")


새탭에서 링크열기. 마크다운 언어에는 없음.
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>



# 이미지 (image)

~[]()

![GOOGLE](https://res.cloudinary.com/demo/image/fetch/fl_png8/https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)


이미지에 링크삽입
[![GOOGLE](https://res.cloudinary.com/demo/image/fetch/fl_png8/https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)](https://google.com)




# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 
간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3



# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.



# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

9
터미널에 입력하는 git같은 코드도 가능.<br/>
$는 터미널코드라는것을 알리기 위함. 실제 코드에선 빼고 작성

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```



# 표 (Table)
( | 버티컬바 = 백스페이스 아래버튼)  
(:--:  가운데 정렬)  
(--:  오른쪽 정렬)


position 속성  

값 | 의미 | 기본값
--|:--:|--:
static | 요소의 배치 기준없음 | O
relative | 요소 자신을 의미 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X



# 원시 HTML ( Raw HTML)

<span style="text-decoration: underline;">동해물</span>과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세


<a href="https://naver.com" 
title="NAVER로 이동!"
target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />




# 수평선 (Horizontal Rule)

---

***

___



