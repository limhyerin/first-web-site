HTML언어를 이용하여 간단한 웹 페이지를 구현해본다.

링크 3가지를 준비하여 각각 페이지를 구현하고 링크에 따라 다른 페이지가 뜨도록 구현하도록 한다.

 <br>

## 전체 기본 웹 페이지
![](https://velog.velcdn.com/images/hrnn00/post/f9b87d32-4d57-41e8-8ba7-80a61fd7e10b/image.png)


```
Source Code
<!doctye html>
<html>
<head>
  <title>WEB1 - Welcome</title>
  <meta charset="utf-8">
</head>

<body>
  <h1><a href="index.html">WEB</a></h1>
  <ul>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ul>

  <h2>WEB</h2>
  <p>
    The World Wide Web (WWW), commonly known as the Web, is the world's dominant software 
    platform.[1] It is an information space where documents and other web resources can be 
    accessed through the Internet using a web browser.[2] The Web has changed people's lives 
    immeasurably.[3][4][5] It is the primary tool billions of people worldwide use to interact
    on the Internet.[6] It was invented by Tim Berners-Lee at CERN in 1989 and opened to the 
    public in 1991.</p>

    <img src="www.jpg" width="100%">
    <p>
    Web resources may be any type of downloadable media. Web pages are documents interconnected
    by hypertext links formatted in Hypertext Markup Language (HTML). The HTML syntax displays
    embedded hyperlinks with URLs, which permits users to navigate to other web resources. 
    In addition to text, web pages may contain references to images, video, audio, and 
    software components, which are either displayed or internally executed in the user's web
    browser to render pages or streams of multimedia content. Web applications are web pages
    that function as application software.</p>
</body>
</html>
```

<br>

## 01 첫번째 웹 페이지
![](https://velog.velcdn.com/images/hrnn00/post/fc207406-f981-4d45-a5be-7f0d861fe760/image.png)

**Source Code**
```
<!doctye html>
<html>
<head>
  <title>WEB1 - HTML</title>
  <meta charset="utf-8">
</head>

<body>
  <h1><a href="index.html">WEB</a></h1>
  <ul>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ul>

  <h2>HTML이란 무엇인가?</h2>
  <p><a href="https://ko.wikipedia.org/wiki/HTML" target="_blank" title="html">Hypertext Markup
  Language (HTML)</a> is the standard markup language for <strong> creating <u>web</u> 
  pages</strong> and web applications. Web browsers receive HTML documents from a web server or 
  from local storage and render them into multimedia web pages. HTML describes the structure of 
  a web page semantically and originally included cues for the appearance of the document.</p>
  <img src="coding.jpg" width="100%">
  <p>HTML elements are the building blocks of HTML pages. With HTML constructs, images and other 
  objects, such as interactive forms, may be embedded into the rendered page. It provides a means
  to create structured documents by denoting structural semantics for text such as headings, 
  paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written
  using angle brackets.</p>
</body>
</html>
```

<br>

## 02 두번째 웹 페이지
![](https://velog.velcdn.com/images/hrnn00/post/5f95f6c6-6827-4879-b741-e7b321dffc5f/image.png)


**Source Code**
```
<!doctye html>
<html>
<head>
  <title>WEB1 - CSS</title>
  <meta charset="utf-8">
</head>

<body>
  <h1><a href="index.html">WEB</a></h1>
  <ul>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ul>

  <h2>CSS란 무엇인가?</h2>
  <p>Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation
  of a document written in a markup language such as HTML or XML (including XML dialects such as 
  SVG, MathML or XHTML).[1] CSS is a cornerstone technology of the World Wide Web, alongside HTML
  and JavaScript.[2]

  <img src="css.jpg" width="100%">
  CSS is designed to enable the separation of presentation and content, including layout, colors,
  and fonts.[3] This separation can improve content accessibility; provide more flexibility and 
  control in the specification of presentation characteristics; enable multiple web pages to share
  formatting by specifying the relevant CSS in a separate .css file, which reduces complexity and
  repetition in the structural content; and enable the .css file to be cached to improve the page
  load speed between the pages that share the file and its formatting.

  Separation of formatting and content also makes it feasible to present the same markup page in
  different styles for different rendering methods, such as on-screen, in print, by voice (via 
  speech-based browser or screen reader), and on Braille-based tactile devices. CSS also has rules
  for alternate formatting if the content is accessed on a mobile device.[4]</p>
</body>
</html>
```

<br>

## 03 세번째 웹 페이지
![](https://velog.velcdn.com/images/hrnn00/post/0a565c24-17c6-4837-bfae-59e715327855/image.png)

**Source Code**
```
<!doctye html>
<html>
<head>
  <title>WEB1 - JavaScript</title>
  <meta charset="utf-8">
</head>

<body>
  <h1><a href="index.html">WEB</a></h1>
  <ul>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ul>

  <h2>JavaScript란 무엇인가?</h2>
  <p>
    JavaScript (/ˈdʒɑːvəskrɪpt/),[10] often abbreviated JS, is a programming language that is 
    one of the core technologies of the World Wide Web, alongside HTML and CSS.[11] As of 2022,
    98% of websites use JavaScript on the client side for web page behavior,[12] often 
    incorporating third-party libraries.[13] All major web browsers have a dedicated JavaScript
    engine to execute the code on users' devices.

  <img src="sr.jpg" width="100%">
  JavaScript is a high-level, often just-in-time compiled language that conforms to the 
  ECMAScript standard.[14] It has dynamic typing, prototype-based object-orientation, and first
  -class functions. It is multi-paradigm, supporting event-driven, functional, and imperative 
  programming styles. It has application programming interfaces (APIs) for working with text,
  dates, regular expressions, standard data structures, and the Document Object Model (DOM).</p>
</body>
</html>
```
 

**결과 화면**

https://limhyerin.github.io/first-web-site/
 
