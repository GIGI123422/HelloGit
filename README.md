# HelloGit

### 3.1 Header
This is an H1
==============

This is an H2
-------------

### 글머리 테스트
# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

### 3.2 BlockQuote
##### 블록인용 문자
> This is a afirst blockqute.
> > This is a afirst blockqute.
> > > This is a afirst blockqute.

### 3.3 목록
##### 순서있는 목록(내림차순으로 자동정렬)
1. 첫번째
2. 두번째
3. 세번째
##### 순서없는 목록
* 빨강
  * 녹색
    * 파랑
+ 빨강
  + 녹색
    + 파랑
- 빨강
  - 녹색
    - 파랑
##### 혼합해서 사용 가능
* 1단계
  - 2단계
    + 3단계
      + 4단계
      
### 3.4 코드블럭
##### 방법1: ```<pre><code>{code}</code></pre>```
<pre>
<code>
public class BootspringBootApplication{
  public static void main(String[] args){
    System.out.println("Hello, Honeymon");
  }
}
</code>
</pre>
##### 방법 2 : ```
```
public class BootspringBootApplication{
  public static void main(String[] args){
    System.out.println("Hello, Honeymon");
  }
}
```

### 3.5 수평선
##### 방법
```
* * *
***
*****
- - -
-----------------------------
```
##### 결과
* * *
***
*****
- - -
-----------------------------

### 3.6 링크
##### 참조링크
```
- [link keyword][id]
- [id]: URL "Optional Title here"
```
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
##### 외부 링크
```
- 사용문법: [Title][link]
- 적용예: [Google](https://google.com, "google link")
```
- Link: [Google](https://google.com, "google link")
##### 자동연결
일반적인 URL 혹은 이메일 주소인 경우 적절한 형식으로 링크를 형성한다.
* 외부링크: <http://example.com>
* 이메일링크: <adress@example.com>

### 3.7 강조
```
- *single asterisks*
- _single underscores_
- **double asterisks**
- __double underscores__
- ~~cancelline~~
```
- *single asterisks*
- _single underscores_
- **double asterisks**
- __double underscores__
- ~~cancelline~~
### 3.8 이미지
- ![Alt text](/path/to/img.jpg)
- ![Alt text](/path/to/img.jpg "Optional title")

### 3.9 이미지 (GitHub)
![고라파덕](https://user-images.githubusercontent.com/43196905/96084322-dbab1500-0ef9-11eb-9bb7-960091043ded.jpg)
