## 1. 제목 (Headers)

`#` 을 사용하여 표현, 1개 부터 6개 까지 사용할 수 있고  
`#` 의 수가 증가할 때 마다 제목 수준이 낮아진다 (글씨가 작아진다.)

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

#### == 또는 --를 사용하여 H1, H2를 사용할 수 있다.
```
H1
==

H2
--
```

H1
=====


H2
------

## 2. 인용 (BlockQuote)

`>`으로 시작하는텍스트
```
>first blockquote
>>second blockquote
>>>third blockquote
```

>first blockquote
>>second blockquote
>>>third blockquote

## 3. 코드 블럭 (Code Blocks)
코드 블럭을 삽입하기 위해서는 앞에 공백 4개 혹은 탭1개를 붙인다.
```
	this is tab code block
```
	this is tab code block

마크다운 변환기에 따라 ``` 또는 ~~~  문자열로 코드 블럭을 감싸 사용할 수 도 있다.

	``` this is ``` code block ```
	~~~ this is ~~~ code block ~~~
```
this is ``` code block
```
~~~
this is ~~~ code block
~~~

코드 블럭을 사용해 프로그램 언어를 표현할 수 있다.
~~~
``` java
public String Hello(String name){
	return "Hello " + name;
}
```
~~~
```java
public String Hello(String name){
	return "Hello " + name;
}
```

## 4. 목록 (Lists)
순서가 없는 목록은 *, +, - 문자를 붙여서 사용한다. (섞어서 사용 가능)

~~~
* List 1
+ List 2
- List 3
~~~
* List 1
+ List 2
- List 3

순서가 있는 목록은 1. 으로 시작한다.
~~~
1. List 1
1. List 2
1. List 3
~~~
1. List 1
1. List 2
1. List 3

목록을 중첩하여 사용할 수 있다.

~~~
1. List 1
2. List 2
	- List 2-1
	- List 2-2
	- List 2-3
3. List 3
~~~

1. List 1
1. List 2
	- List 2-1
	- List 2-2
	- List 2-3
1. List 3

## 5. 강조 (Emphasis)
기울여 쓰기(italic)는 `*`또는 `_`로 텍스트를 감싼다.
굵게 쓰기(bold)는 `**` 또는 `__`로 텍스트를 감싼다.

~~~
`*` 을 이용한 *기울여 쓰기* 
`_` 을 이용한 _기울여 쓰기_
~~~
`*` 을 이용한 *기울여 쓰기* 
`_` 을 이용한 _기울여 쓰기_

~~~
`**` 을 이용한 **굵게 쓰기**
`__` 을 이용한 __굵게 쓰기__
~~~
`**` 을 이용한 **굵게 쓰기**
`__` 을 이용한 __굵게 쓰기__

~~~
*기울여 쓰기*와 **굵게 쓰기** 그리고 ***기울이면서 굵게*** 쓰기
~~~
*기울여 쓰기*와 **굵게 쓰기** 그리고 ***기울이면서 굵게*** 쓰기

## 수평선 (Horizontal Rules)

`-`  또는 `*` 또는 `_`을 3개 이상 작성한다.

~~~
***
---
___
~~~
***
---
___

## 6. 링크 (Links)

### 인라인 링크 : `[Title](Link url "link title")`
~~~
Google 링크 실습 : [Google](http://www.google.com "link title") "go google"
~~~
Google 링크 실습 : [Google](http://www.google.com "go google")
link title은 생략 가능하다.

### 참조 링크 : `[Title][id]` `[id]: Link url "link title"`
~~~
Google 링크 실습 : [Google][1]
github 링크 실습 : [Github][2]

[1]: http://google.com "google link"
[2]: http://github.com "github link"
~~~
Google 링크 실습  [Google][go google] 
github 링크 실습  [Github][go github] 

[go google]: http://google.com "google link"
[go github]: http://github.com "github link"

### URL 링크 : `<url>`
~~~
구글 홈페이지는 <http://google.com>
메일 주소는 <example@gmail.com>
~~~
구글 홈페이지는 <http://google.com>
메일 주소는 <example@gmail.com>

## 7. 이미지

마크다운에서 이미지 사이즈 조절 기능은없기 때문에 이미지 사이즈를 조절하고 싶은 경우에는`<img width="" height=""></img>`를 사용해야 한다.
~~~
![alt text](path)
![alt text](path "image title")
~~~

~~~
![alt text](https://cdn.guidingtech.com/media/assets/WordPress-Import/2014/01/markdown-logo2-300x201.png)
~~~
![alt text](https://cdn.guidingtech.com/media/assets/WordPress-Import/2014/01/markdown-logo2-300x201.png)

