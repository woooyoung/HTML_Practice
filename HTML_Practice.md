# HTML_Practice
## visual studio
### html 01
Hello World

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>First day</title>
</head>
<body>
<div>
<p title="할만한데?">첫 날 입니다.<br>어려워요.</p>
<a href="https://github.com/woooyoung/practice"> 눌러주세요</a>
<hr />
<img src="https://avatars1.githubusercontent.com/u/63499356?s=40&v=4" width="100" heigth="100"  alt="이미지가 없습니다."/>
</div>
<div>
<video src="https://www.youtube.com/watch?v=61uXIqHCg3s" width="100" alt="영상자리입니다" />
<br />
</div>
<span>유튜브 첫 화면 첫 영상</span>
</body>
</html>
```


### html02
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>2nd day</title>
</head>
<body>
<h1>둘쨰 날 입니다.</h1>
<p>아직 뭘 해야 할지 모르겠어</p>
<p>이것 저것 <br>넣어보는 중</p>
<button>Click me</button>
<p style="color:red">이건 빨간색 </p>

</body>
</html>
```


### html03
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>3rd day</title>
</head>
<body>
<pre>셋째 날 입니다. 
html기초 공부 중
서버가 돌아가지 않는데 이유를 못 찾는 중
</pre>
<body style="background-color:powderblue;">
<p style="font-family:courier;">바탕체 계열</p>
<p style="font-size:160%;">폰트 사이즈 160%</p>
<p style="text-align:right;">문단 우측 정렬 </p>
</body>
</html>
```

### html04
```html
<html>
<head>
<meta charset="UTF-8">
<title>4th day</title>
</head>
<body><p>html 공부 시작 4일</p>
<p>아직 원인을 모르겠어요</p>
<h2>이건 <small>작은</small>글자</h2>
<p>이게<del>이거</del>였구나</p>

<blockquote cite="인용한 웹 주소">
인용문 입니다.
</blockquote>
<bdo dir="rtl">거꾸로 쓰는 중</bdo>
<!-- 코멘트 브라우저 상에 나타나지 않음 -->
<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.2);">rgba(255, 99, 71, 0.2)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.4);">rgba(255, 99, 71, 0.4)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.6);">rgba(255, 99, 71, 0.6)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.8);">rgba(255, 99, 71, 0.8)</h1>
<h1 style="background-color:rgba(255, 99, 71, 1);">rgba(255, 99, 71, 1)</h1>
<!-- RGB 색 참고 -->
<h1 style="background-color:#ff0000;">#ff0000</h1>
<h1 style="background-color:#0000ff;">#0000ff</h1>
<h1 style="background-color:#3cb371;">#3cb371</h1>
<h1 style="background-color:#ee82ee;">#ee82ee</h1>
<h1 style="background-color:#ffa500;">#ffa500</h1>
<h1 style="background-color:#6a5acd;">#6a5acd</h1>
<!-- HEX 색 참고 -->
<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h1>
<!-- HSL 색 참고 -->
</body>
</html>
```

### html05-1
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>5th day</title>
<style>
body {background-color: black;}
h1   {color: yellow;}
p    {color: white;}
#p01 {
  color: grey;
}
</style>
</head>
<body>
<h1>Internal CSS: 내부 스타일 시트</h1>
<p>HTML문서내에서 head사이에 스타일을 정의하는 방법이다.</p>
<p id="p01">이 문장만 다르게 할 수도 있다.</p>
</body>
</html>
```


### html05-2
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>5th day</title>
</head>
<body>
<h1>CSS: stands for Cascading Style Sheets.</h1>
<p style="color:blue; font-family: courier; font-size: 300%;"> Inline Styles(HTML 태그 내에 스타일 지정): 
스타일을 적용하고 싶은 HTML태그안에서 정의하는 방법이다.</p>
<p>External Style Sheet(외부 스타일 시트): css라는 확장자를 가진 스타일 시트 파일을 만들고 이 파일을 HTML 문서에 연결하여 사용하는 방법이다.</p>

</body>
</html>
```


### html06
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>6th day</title>
<style>
div.first {
  opacity: 0.3;
}
h1 {
  background-color: lightblue;
}
</style>
</head>
<body>
<h1 style="border: 3px solid Tomato;">여섯 째 날 입니다.</h1>
<pre>현재 html,css,포토샵,일러스트
공부를 병행 하고 있어요.
할 공부가 넘치는데 시간은 빨리 가는 기분입니다.</pre> <!-- 사실 포토샵과 일러스트 위주로 하는 중 -->
<div class="first">
  <p>opacity 0.3</p> <!-- 불투명도 -->
</div>
</body>
</html>
```


### html07
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>7th day</title>
<style>
body {background-color: lightgrey;}
h1   {color: royalblue;}
h3   {color: lightcoral}
p    {color: black;}
p    {text-indent: 20px;}
a {
  color: blue;
}
</style>
</head>
<body>
<h1>오늘은 한 것 들을 좀 정리 해보려 합니다.</h1>
<p>1. photoshop : 현재 cs6 version으로 공부 중 입니다.<br> 기본적인 툴 사용법을 익히고 있습니다.</p>
<p>2. illustrator : cc version으로 공부 중 입니다.<br> 위와 마찬가지로 기본적인 사용 법을 익히고 있습니다. </p>
<p>3. html,CSS : <a href="https://www.w3schools.com/html/">w3school.com</a>을 참고하여 공부 하고 있습니다.<br>
예상보다 양이 방대하여 이것 저것 경험해 보는 것에 중점을 두고 있습니다.</p>
<p>4. java : 이론 적인 부분을 공부하고 있습니다.</p>
<h3>이번 주말에 좀 더 상세하게 정리하여 내가 할 수 있는 부분과 앞으로 공부 할 부분을 파악 해보겠습니다.</h3>
</body>
</html>
```

### html08
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>8th day</title>
<style>
body {background-color: white;}
h1   {color: rosybrown;}
p    {color: black;}
p    {text-indent: 10px;}
td   {color: black}
th   {color:brown}
caption {color:chocolate}
table, th, td {
  border: 2px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 6px;
}
</style>
</head>
<body>
  <h1>정리해 보자면</h1>
  

  <table style="width: 50%">
    <caption>공부 한 영역</caption>
    <tr>
      <th>photoshop</th>
      <th>illustrator</th> 
      <th>html</th>
      <th>JAVA</th>
    </tr>
    <tr>
      <td>선택윤곽 도구</td>
      <td>선택,직접 선택 도구</td>
      <td>Elements</td>
      <td>특징</td>
    </tr>
    <tr>
      <td>올가미 도구</td>
      <td>올가미 도구</td>
      <td>Attributes</td>
      <td>제어</td>
    </tr>
    <tr>
      <td>빠른 선택 도구</td>
      <td>펜 도구</td>
      <td>Headings</td>
      <td>타입</td>
    </tr>
    <tr>
      <td>브러쉬 도구</td>
      <td>문자 도구</td>
      <td>Paragraphs</td>
      <td></td>
    </tr> 
    <tr>
      <td>스탬프 도구</td>
      <td></td>
      <td>Styles</td>
      <td></td>
    </tr> 
    <tr>
      <td>그라데이션 도구</td>
      <td></td>
      <td>Text Formatting</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>Links</td>
      <td></td>
    </tr>
  </table>
<p>CSS는 내용이 방대하여 추후 따로 정리해 보도록 한다.</p>

  <!--영역에 따른 내용 정리가 필요하다.-->
</body>
</html>
```

### html09
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>9th day</title>
    <style> 
    .first {background-color: black;}
    .second {background-color: brown;}
    .third{background-color: white;}
    body{background-color: grey;}
    h1{color:yellowgreen}
    p{color:white}
    #p01{color:black}
    </style>
    
</head>
<body>
    <h1><span style="border:1px solid red">아홉</span> 째 날</h1>
    <br><div class="first"><p>visual studio code의 사용빈도가 eclipse의 사용빈도를 넘었다.</p></div>
    <br><div class="second"><p>손에 익기 전에 도움을 받는 느낌이어서 좋긴 하지만 실질적으론 도움이 되지 않을 것 같다</p></div>
    <br><div class="third"><p id=p01>1일 1commit을 목표로 하고 있지만 쉽지 않아, 습관을 들이는게 중요할 것 같다.</p></div>

</body>
</html>
```

### html10
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>10th day</title>
        <style>
            h1{color:gold;,font-size: 5px;}
            body{background-color:snow;}
            p{color:black;,font-size: 3px;}
            h2{color:gray}
            p{text-indent: 15px;}
            ul{color:grey}
            li{color:black}
        </style>

    </head>
    <body>
        <h1>자바스크립트(JavaScript)</h1>
        <h2>기초</h2>
        <p>1.자바스크립트는 html의 내용을 바꿀 수 있다.</p>
        <!--getElenentById() 를 이용하여 요소를 가져온다.-->
        <!--document.getElementById().innerHTML = "Hello JavaScript";-->
        <p>2.자바스크립트는 html의 속성값을 바꿀 수 있다.</p>
        <!--getAttribute() 는 선택한 요소의 속성값을 가져온다.-->
        <p>3.자바스크립트는 html의 스타일을 변경할 수 있다.</p>
        <!--CSS 속성을 이용하여 태그에 직접 설정할 수 있다.-->
        <!--document.getElementById().style.fontsize = "10px";-->
        <p>4.자바스크립트는 html 요소를 숨길 수 있다.</p>
        <!--document.getElementById().style.display ="none";-->
        <p>5.자바스크립트는 html 요소를 나타낼 수 있다.</p>
        <!--document.getElementById().style.display = "block";-->
        <br><h2>위치</h2>
        <p>1.html에서는 script태그 내에 입력한다.</p>
        <!--<script>-->
        <p>2.자바스크립트는 head,body 또는 양 쪽에 자 위치할 수 있다.</p>    
        <p>3.외부에도 위치가 가능한데 이는 script 태그의 src(소스)속성에 넣는다.</p>
        <!--<script src="myScript.js"></script>-->
        <ul>장점
            <li>html과 코드를 분리한다.</li>
            <li>쉽게 읽고 관리 할 수 있다.</li>
            <li>캐시 된 자바스크립트 파일은 pageload 속도를 높일 수 있다.</li>
        </ul>
    </body>
</html>
```

### html11
```html
<!DOCTYPE html>
<html>
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!--viewport:화면 상의 표시 영역-->
    <!--divice~장치의 크기에 맞춰서-->
    <!--initial-scale:초기 화면 배울(zoom레벨)-->
    <!--브라우저의 크기를 조정하면 변한다.-->
    <title>11th day</title>
    <!--content-box : 콘텐트 영역을 기준으로 크기를 정합니다.
         border-box : 테두리를 기준으로 크기를 정합니다.
          initial : 기본값으로 설정합니다.
           inherit : 부모 요소의 속성값을 상속받습니다.-->
    <!--@media:반응 형 레이아웃-메뉴와 내용 (섹션 내부)을 나란히 놓지 않고 서로 위에 놓습니다.-->
    <style>
        {box-sizing: border-box;
        }
        body{font-family: Arial, Helvetica, sans-serif;}
        header{background-color: darkgray;
        padding:30px;
        text-align:center;
        font-size: 30px;
        color:black}


        section{display: -webkit-flex;
                display: flex;}
        nav{-webkit-box-flex: 1;]
        -ms-flex:1;
        background:yellow;
        padding:20;
        }
        nav ul{list-style-type:square;
        padding:0;
        color: black;
        }
        article{-webkit-webkit: flex 3;
        -ms-webkit: flex 3;
        flex:3;
        background-color:lightskyblue;
        padding:10px;
        color:red
        }
        footer{background-color: gray;
        padding: 10px;
        text-align: right;
        color:blue;
        }
        @media (max-width: 600px;){
            section{-webkit-flex-direction: column;
            flex-direction:column}
        }

        
    </style>
    
        
</head>
<body><h1>CSS의 레이아웃에 대하여</h1>
    <header><h2>여기는 header자리</h2></header>
    <section>
        <nav>
            <ul>
                <li>여기는</li>
                <li>nav</li>
                <li>자리</li>
            </ul>
        </nav>
        <article><h2>여기는</h2>
            <p>article</p>
        <p>자리</p></article>
    </section>
    <footer><p>이 곳은 footer</p></footer>
</body>
</html>
```

### html12
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>12th day</title>
    </head>
    <body>
        <h1>반응형 웹 디자인?</h1>
        <p>html,CSS를 이용하여 웹사이트의 크기를 자동으로 조정,숨기기,축소,확대하여 모든 장치에서 보기 편하도록 한다.</p>
        
        <ul><li>viewprot</li>
        <!--<meta name="viewport" content="width=device-width, initial-scale=1.0">
        의 유무로 기기에서 변화 하는 모습을 확인 했다.-->
        <li>images</li>
        <!--<img src="img_girl.jpg" style="width:100%;"> 
            :너비 속성을 100%로 설정하면 이미지가 반응형이 된다.-->
        <li>text</li>
        <!--<h1 style="font-size:10vw">Hello World</h1>
        :vw=> view-width(뷰포트 너비)로 브라우저 창 크기에 텍스트 크기를 따라가게 한다. -->
        <li>media</li>
        <!--Media Queries를 사용하여 다양한 브라우저 크기에 다른 스타일을 정의 할 수 있다.
        참조::https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_media_query3-->
        </ul>
        <p>기본 CSS, jQuery, 또는 Bootstrap을 이용한다.</p>

    </body>
</html>
```

### html13
```html
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title>13th day</title>

</head>
<body>
    <h2>근황</h2>
    <pre>조금 혼란스럽다. 현재 html,CSS,photoshop,illurstrator 기초 공부를 하는중인데, 
원래 취약했던 부분인 JAVA를 추가하자니 머리가 뒤죽박죽이다. 
원래는 git도 공부하는 동안은 일기 형식으로 그 날의 주제에 맞게 작성 해보려 했으나, 
하루에 다른 영역을 왔다 갔다하는 느낌이어서 어떤 것을 주제로 삼아야 하는지 감을 못 잡는 중이다.
여기에 디자인적 요소까지 추가 된다면 방향성과 정체성을 잃을 것 같다. 
생각을 정리 할 시간이 필요하지만 진행하던 영역을 쉬면 그 부분을 잊어버리게 되어 효과는 떨어질 듯 하다. 
내일 디자인 세미나가 있으니 한 번 들어보고 나서 프론트엔드와 백엔드의 방향이라던가, 어느 곳을 어떻게 공부해야
더 효율적일지 고민 해봐야겠다. (항상 얖에서 도움을 주는 친구에게는 매우 고맙게 생각하고 있다.)
    </pre>
</body>
```

### html14
```html
<!DOCTYPE html>
<head>
    <meta charset="UTf-8">
    <title>14yh day</title>

</head>
<body>
    <h1>CSS의 위치속성</h1>
    <p>position 속성은 요소에 사용되는 위치 결정 방법의 유형을 지정한다.</p>
    <ul>
        <li>static</li>
        <li>relative</li>
        <li>fixed</li>
        <li>absolute</li>
        <li>sticky</li>
    </ul>
    <p>요소는 top, bottom, left, right의 속성을 사용하여 배치하는데<br>position 속성을 먼저 설정하지 않으면 작동하지 않는다.</p>
    <br><p>static:정적 ->>html요소는 기본적으로 정적 위치에 있고, top, bottom등의 속성에 영향을 받지 않는다.</p>
    <br><p>relative: 상대->>정상 위치를 기준으로 일반 위치에서 멀어지도록 조정된다.  </p>
    <br><p>fixed: 고정->>뷰포트에 상대정으로 배치. 페이지가 스크롤 되어도 항상 같은위치에 유지된다.</p>
    <br><p>absolute: 절대->>고정 된 것처럼 뷰포트에 배치되는 대신 가장 가까운 위치에 위치한 조상에 대해 배치된다.</p>
    <br><p>sticky: 사용자의 스크롤 위치를 기준으로 배치된다. </p>
</body>
```

## Brackets
### Text 관련 태그 01
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width = device-width, initial-scale = 1.0">
        <meta http-equiv="X-UA-Compatible" content = "ie=edge">
        <title> 텍스트 관련 태그 </title>
    </head>
    
    <body>
    <h1>제목태그, 제목을 나타내고 구분짓는 태그</h1>
        <h2>header</h2>
        <h3>header</h3>
        <h4>header</h4>
        <h5>header</h5>
        <h6>header</h6>
        
        <p>단락태그, <br/>본문을 나타내기 위한 태그</p>
        <!-- h태그와 p태그는 서로 상속 될 수 없음! -->
        
        <!--수평선을 나타내는 태그 / 단락을 구분짓는 용도로 사용-->
        <hr/>
        <p>인용문을 나타내는 태그</p>
        <blockquote>이 글은 인용 되었습니다.</blockquote>
        
        <h1>imagine</h1>
        <hr/>
        <p>imagine there's no heaven It's easy if you try<br/>No hell below us Above us only sky Imagine all the people</p>
        <hr/>
        <blockquote>John Lennon</blockquote>
        <hr/>
        <pre>
                공백이나 줄 바꿈 결 과 값 을 
               그대로 보여주는 태그</pre>
        
    </body>
</html>
```

### Text 관련 태그 02
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width = device-width, initial-scale = 1.0">
        <meta http-equiv="X-UA-Compatible" content = "ie=edge">
        <title> 글자를 꾸며주는 태그 </title>
    </head>
    
    <body>
        <strong>글자를 굵게- 중요한 것들을 강조</strong><br/>
        <b> 글자의 굵기- 굵은 글꼴</b><br/>
        <hr/>
        <em>이탤릭체로 표현</em><br/>
        <i>주변의 문장과 다른 의미의 느낌을 표현</i><br/>
        <hr/>
        <mark>형관펜 같은 표현- 부분의 강조(색채움)</mark>
        <hr/>
        <ins>글자아래 밑줄</ins><br/>
        <u>밑줄표현</u><br/>
        <del>취소선 표현</del>
        
        <hr/>
        
        글자가 아래로 작아지는 <sub>아래첨자</sub><br/>
        글자가 위로 작아지는 <sup>위첨자</sup><br/>
        
        <hr/>
        
        <span>글자를 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;꾸며주는 역할</span>
        
        <hr/>
        
        <!--ul > 목록태그 / 순서가 없는 목록태그
            ol > 목록태그 / 순서가 있는 목록태그
            
            ul,ol > li(필요)-->
        <ul>
        <li>순서가 없는 목록태그</li>
        <li>앞에 자동으로 부호가 생성</li>
        <li>네비게이션 메뉴 - 중요!</li>
        </ul>
        
        <ol>
        <li>순서가 있는 목록태그</li>
        <li>앞에 자동으로 순서가 생성</li>
        <li>많이 사용하지 않음</li>
        </ol>
        
        <hr/>
        
        <!--정의 목록태그 : 특정 용어와 정의를 설명할때 사용-->
        <dl>
        <dt>정의 될 단어</dt>
        <dd>정의 할 내용, 정의 될 내용</dd>
        </dl>
    </body>
</html>
```

### Table 관련 태그
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width = device-width, initial-scale = 1.0">
        <meta http-equiv="X-UA-Compatible" content = "ie=edge">
        <title> Table 관련 태그 </title>
    </head>
    
    <body>
        <!--<table border="1" cellpadding="10" cellspacing="5" width="500">
        <tr>
            <th>title</th>
            <th>title</th>
            <th>title</th>
            </tr>
            <tr>
            <td width="150">table_1</td>
            <td width="100">table_1</td>
            <td width="250">table_1</td>
            </tr>
            <tr>
            <td height="80">table_1</td>
            <td>table_1</td>
            <td bgcolor="#f00">table_1</td>
            </tr>
        </table>
        -->
        <h1>셀의 병합</h1>
        <!--2줄 2칸-->
        <!--가로로 병합, colspan="가로로 묶을 칸의 합"-->
        <table border="1" cellpadding="0" cellspacing="0">
        <tr>
            <th colspan="2">colspan</th>
        </tr>
        <tr>
            <td>가로병합</td>
            <td>가로병합</td>
         </tr></table><br/>
        <!--새로로 병합, rowspan="세로로 묶을 칸의 합"-->
        <table border="1" cellpadding="0" cellspacing="0">
        <tr>
            <th rowspan="2">rowspan</th>
            <th>rowspan</th>
        </tr>
        <tr>
            <td>세로병합</td>
         </tr>
        </table><br/>
        
        <!--caption : 해당 테이블의 표의 의미, 타이틀-->
        <table border="1">
        <caption>테이블의 제목</caption>
        <tr>
            <td>table_1</td>
            <td>table_2</td>
            </tr>
        </table>
    </body>
</html> 
```
