# 프론트 엔드 개발 

## 표기법 : 
 - 사용자가 이름을 지정하는 경우
 - 여러 단어를 사용해서 이름을 지정하는 경우 

```
html-css : kebab case

html_css : snake case - Python

htmlCss : Camel Case - Javascript , JAVA, C, C++

HtmlCss : Pascak Case - Javascript , JAVA, C, C++   ( Class )

Web Front End
- HTML( class, id ) : kebab case
- File/Folder name : snake case
- Js : Camel case   <- 규칙
- Js - Class : Pascal Case   <- 규칙

```

## HTML

### HTML Introduction
https://www.w3schools.com/html/html_intro.asp

> 웹페이지 구조 표시
>
> 윂페이지 콘텐츠 표시
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

` <= backtick
```
<tagname> CONTENTS</tagname>

** 시작태그만 있는 Element : Empty element
```

### HTML Element
https://www.w3schools.com/html/html_elements.asp

> 포함관계
> - 기준에 따라서 조상요소(Ancestor), 부모요소(Parent), 자식요소(Child), 자손요소(Descendant)

```
<html>
  <body>
    <h1>Web page</h1>
  </body>
</html>

* html : body의 부모요소, h1의 조상요소 

* body : html의 자식요소, h1의 부모요소

* h1 : html의 자손요소, body의 자식요소
```

### HTML Attributes
https://www.w3schools.com/html/html_attributes.asp

### HTML Heading
https://www.w3schools.com/html/html_headings.asp

### HTML Paragraph
https://www.w3schools.com/html/html_paragraphs.asp

### HTML Hyperlink
https://www.w3schools.com/html/html_links.asp

a : Anchor(닻)
href : Hypertext REFerence

### HTML URL
https://www.w3schools.com/html/html_urlencode.asp

인터넷 주소
- IP(Internet Protocol) 주소 : 192.168.0.1
- 도메인(Domain Name) 주소 : www.naver.com (와 같은 것) 
- Domain -> DNS(Domain Name Server/System -> ip

URL(Uniform Resource Locator)
- 자세한 주소
- 도메인주소 + 해당 페이지 폴더 위치/파일 위치
- 인터넷 주소를 표현하는 가장 큰 범위
- 프로토콜 : http, https, ftp ...

### HTML File Path
https://www.w3schools.com/html/html_filepaths.asp

절대 경로
- 출발 지점에 상관없이 항상 같은 리소스를 찾을 수 있도록 표시하는 주소/경로
- 장점 : 항상 같은 자원의 위치로 찾아올 수 있음
- 단점 : 주소 표시 길이가 길다
- Ex) 도메인주소/파일경로 : https://www.w3schools.com/html/html_filepaths.asp

상대 경로
- 출발 지접을 기준으로 리소스 경로를 표시하는 주소/경로
- 장점 : 주소 표시 길이가 상대적으로 짧음
- 단점 : 기준에 따라서 표시 방식이 매번 달라짐
- Ex) 파일(폴더) 경로 : html/html_filepath.asp , ../html/html_filepath.asp
- Ex) 루트 상대 경로 : /html/html_filepath.asp


### HTML
https://www.w3schools.com/html/html_tables.asp

table generator (테이블 잘 사용안하고 만들기 귀찮으므로 간단하게 만들어주는 사이트)
https://www.tablesgenerator.com/html_tables

### HTML LIst
https://www.w3schools.com/html/html_lists.asp

중첩목록(Nestsed List) : 여러 수준(레벨)으로 구성된 목록

### HTML Images
https://www.w3schools.com/html/html_images.asp

alt = alternative

### HTML Video
https://www.w3schools.com/html/html5_video.asp

### HTML Youtube
https://www.w3schools.com/html/html_youtube.asp

















