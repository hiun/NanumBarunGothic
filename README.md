# 나눔바른고딕 웹폰트

English docs are avaliable on [here][english-version]

네이버에서 2013년 10월 한글날등을 기념하여 만든 [나눔바른고딕][naver]을 웹폰트로 제작하였습니다.
제작 의도는 제 개인적인 사용이 목적이 었으며, 구글 웹폰트등 정식 배포 서비스가 나오면 그것을 사용해 주시기 바랍니다. 
(그렇다고 이것을 사용하지 말라는 것은 아닙니다.)

## 시작하기

나눔바른고딕 웹폰트는 2가지 형태으로 사용할수 있습니다.

**기본**

웹사이트HTML문서의 ``<head>``안에 아래 코드를 붙혀 넣으시면 됩니다.
```
<link href='http://www.openhiun.com/hangul/nanumbarungothic.css' rel='stylesheet' type='text/css'>
```

**@import**

웹사이트HTML문서의 ``<head>``안의 스타일 시트에 아래 코드를 붙혀 넣으시면 됩니다.
```
@import url(http://www.openhiun.com/hangul/nanumbarungothic.css);
```

## 적용하기

폰트를 적용하려면 폰트 이름을  적용하길 원하는 CSS에 다음과 같이 추가하시면 됩니다.
```
font-family: 'Nanum Barun Gothic', sans-serif;
```

예를들어 폰트를 body에 적용시키고 싶다면 아래처럼 하시면 됩니다.
```
<style type="text/css">
body {
  font-family: 'Nanum Barun Gothic', sans-serif;
}
</style>
```

혹은 text라 불리는 클래스에 적용시키고 싶으시다면 아래와 같겠죠?
```
<style type="text/css">
.text {
  font-family: 'Nanum Barun Gothic', sans-serif;
}
</style>
```

## 데모

[데모 페이지][demo]에서 나눔바른고딕을 적용한 페이지를 보실수 있습니다.


# Nanum Barun Gothic Web Fonts

In October 2013, South Korea's biggest internet portal [Naver.com][navermain] has released 'Nanum Barun Gothic' font to 
celebrating 'Hangul Day' and encouraging usage of hangul. I created Nanum Barun Gothic to web fonts for my personal needs. 
Everyone is welcome to use this and sooner or later Google Web API are supporting Nanum Barun Gothic, I recommand use that instead of this.
(But it dosen't mean do not use this.)

## Getting Started

Nanum Barun Gothic web fonts are available on 2 different way.

**Standard**

To use font, insert below code to ``<head>``tag on your HTML document.
```
<link href='http://www.openhiun.com/hangul/nanumbarungothic.css' rel='stylesheet' type='text/css'>
```

**@import**

To use font, insert below code to stylesheet in``<head>``tag on your HTML document.
```
@import url(http://www.openhiun.com/hangul/nanumbarungothic.css);
```

## Applying

To applying font, add below code into your stylesheet.
```
font-family: 'Nanum Barun Gothic', sans-serif;
```

For instance, if you want applying font on body doing like this.
```
<style type="text/css">
body {
  font-family: 'Nanum Barun Gothic', sans-serif;
}
</style>
```

or applying font on class name like text, code is something like below? 
```
<style type="text/css">
.text {
  font-family: 'Nanum Barun Gothic', sans-serif;
}
</style>
```

## Demo
You can checkout Nanum Barun Gothic applied page at [Demo Page][demo]

[english-version]: https://github.com/openhiun/hangul#nanum-barun-gothic-web-fonts
[naver]: http://hangeul.naver.com/
[demo]: http://www.openhiun.com/hangul/
[navermain]: http://www.naver.com
