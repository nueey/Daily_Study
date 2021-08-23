## Daily_Study

### HTML 문서의 기본 구조
 ```
 <html>는 웹 문서의 시작을 알리는 html 태그\
 &lt;head&gt;는 웹 브라우저에 문서 정보를 알려주는 태그\
 &lt;title&gt;는 문서 제목을 나타내는 태그
 ```
### HTML 목록 실습
&lt;!DOCTYPE html&gt;\
&lt;html lang="ko"&gt;\
&lt;head&gt;\
  &lt;meta charset="UTF-8"&gt;\
  &lt;title>탐라국 입춘굿&lt;/title&gt;\
  &lt;link rel="stylesheet" href="css/poster.css"&gt;\
&lt;/head&gt;\
&lt;body&gt;\
    &lt;ol&gt;\
        &lt;li&gt;입춘맞이 : 1/27(월) ~ 1/31(금)&lt;/li&gt;\
        &lt;li&gt;낭쉐코사 : 2/1(토)&lt;/li&gt;\
        &lt;li&gt;거리굿 : 2/2(일)&lt;/li&gt;\
        &lt;li&gt;열림굿 : 2/3(월)&lt;/li&gt;\
        &lt;li&gt;입춘굿 : 2/4(화)&lt;/li&gt;\
      &lt;/ol&gt;\
&lt;/body&gt;\
&lt;/html&gt;

### 실행결과
<!DOCTYPE html>
<html lang="ko">
<body>
    <ol>
        <li>입춘맞이 : 1/27(월) ~ 1/31(금)</li>
        <li>낭쉐코사 : 2/1(토)</li>
        <li>거리굿 : 2/2(일)</li>
        <li>열림굿 : 2/3(월)</li>
        <li>입춘굿 : 2/4(화)</li>
      </ol>
</body>
</html>

***&lt;ol&gt;과 &lt;li&gt;는 순서있는 목록을 입력하군!***
 
### HTML 표 만들기 실습
+ 표의 시작과 끝을 알려주는 &lt;table&gt;과 &lt;/table&gt; 태그를 표시하고
+ 표에 제목을 붙이고 싶다면 &lt;table&gt; 태그 바로 아랫줄에 &lt;caption&gt; 태그를 사용한다.
+ &lt;tr&gt; 태그는 행을 만들고 &lt;td&gt; 태그는 행안에 셀을 만든다








