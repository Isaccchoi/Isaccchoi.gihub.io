---
layout: post
title: "Python tutorial -2"
date: 2017-09-12 10:08:00 +0800
lang: en
nav: post
category: Programing
tags: [Python, ]
---

### 문자열
--

#### 표현
Python3에서는 기본이 Unicode 사용


```
"문자열"
'문자열'
```

둘다 사용 가능


```
긴문자열 입력시 '''
기이이인
문자열
'''으로 묶는다
```

긴문자열은 '''으로 묶는다

```
'문자열1' + '문자열2'
```
문자열 합산도 가능하다

#### 이스케이핑
이스케이프 문자|설명
---|---
\a	| 비프음 발생
\t	| 탭(tab)
\n	| 줄바꿈
\\	| \\(역슬래시) 입력
\\'	| 작은따옴표(') 입력
\\"	| 큰따옴표(") 입력

#### 인덱스
```
>>> lux = "빛으로 강타해요!"
>>> lux[0]
>>> "빛"
>>> lux[1]
>>> "으"
```
문자로 이루어진 리스트이기 때문에 순서로 기록함
#### 슬라이스
```
문자열[Start:End:Step]
```
Start에서 End까지 Step을 기준으로 움직이며 나타냄
-를 사용하여 역순으로 가능
#### 길이
```
len()
```
#### 문자열 나누기(split)
```
split()
```
String의 내장함수 split을 사용하여 비워놓을 경우 공백을 기준으로 필요한 조건이 있을경우 따옴표로 묶어 괄호() 안에 적어 넣는다.
#### 문자열 합치기(join)

```
"넣을문자열".join(넣을 리스트)
```
join함수를 이용해 문자를 넣을 수 있음

### 공식문서
[Text Sequence - String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)


> 참조: https://github.com/Fastcampus-WPS-6th/Python
